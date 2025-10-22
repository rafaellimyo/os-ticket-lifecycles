<h1 align="center">

![OIP](https://github.com/user-attachments/assets/693fd702-ffe0-42a4-8093-d7d101279429)



</h1>

## OS TICKET LIFECYCLE 
This tutorial outlines the demostration of navigating within OS ticket


# Environments and Technologies Used
- osTicket (Help Desk Ticketing System)
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Windows 10 Professional x64 22H2

# Ticket Lifecycle Stages
- Intake
- Assignment & Communication
- Working the Isssue
- Resolution

# Ticket Lifecycle Stages: Intake to Resolution 
## Intake
1. Head to http://localhost/osTicket/ and click the 'Open a New Ticket' button.


<img width="1548" height="918" alt="Screenshot 2025-10-21 220511" src="https://github.com/user-attachments/assets/6d75c2aa-f76e-42c8-aaaf-3a2dea27a0b8" />

2. Fill out the following fields for ticket information
   - Email Address: Email address of whoever is submitting 
   - Full Name: Full name of whoever is submitting the ticket
   - Help Topic: Click on the dropdown menu and select the issue which best describes the issue
   - Issue Summary: Enter a brief summary for the issue and add any needed information
  
   <img width="1545" height="1372" alt="Screenshot 2025-10-19 221751" src="https://github.com/user-attachments/assets/2535a908-f79c-4115-89b2-053d76f1a02c" />

   ## Assignment & Communication
   1. Head to http://localhost/osTicket/scp/login.php and enter the credentials for the administrator that will assign an agent to work on the ticket
<img width="1553" height="970" alt="Screenshot 2025-10-19 222101" src="https://github.com/user-attachments/assets/6d470392-9516-4460-898a-afd91c02c785" />

2. Head to 'Tickets' -> 'Open' and then open the ticket number under the **Ticket** column
   <img width="1548" height="760" alt="Screenshot 2025-10-19 222011" src="https://github.com/user-attachments/assets/e0860d8c-8144-42c9-bc86-d0a170153eba" />

3. Set the Priority, Assign Department, Assigned to, and the SLA Plan values for this ticket.
   In the example below, the admin chooses `Rakai Jenkins` as the **Assignee**
   <img width="1410" height="550" alt="Screenshot 2025-10-19 225410" src="https://github.com/user-attachments/assets/04a9ef66-aba9-4593-8faf-25bd19bc79f8" />
   After the agent has been assigned, the admin set the **Priority** to `High`, the **Department** to `Support`, and the **SLA PLAN** to `Sev-A`

4. Within the ticket lab, you can see a threat or any updates that have been made to the ticket. Once finished, click the 'Post Reply' button and the ticket will be assigned to the appropriate departments and your customer will be notfied of this change.

 ## Working the Issue
 1. Head to `http://localhost/osTicket/scp/login.php` and enter the credentials of the agent who has been assigned to this ticket
    <img width="1553" height="1148" alt="Screenshot 2025-10-22 090911" src="https://github.com/user-attachments/assets/4512b736-c9fa-4f49-902d-cea0edee01e5" />

 2.  Once logged in the agent will ticket featues: who submitted the ticket, time of ticket, priority level, last updated, subject who it is assigned to.
<img width="1550" height="1167" alt="Screenshot 2025-10-22 091311" src="https://github.com/user-attachments/assets/da19843b-db10-4c20-8c13-8303a22a68fd" />

   
 3.  Once the agent has reviewed all the necessary information and identified the problem, the agent could use the **Post Reply** button to the user (Benny Hanna) everything, including the solution.
    <img width="1542" height="1196" alt="Screenshot 2025-10-22 091819" src="https://github.com/user-attachments/assets/77e61050-fd4f-4575-8957-d8f9c77464f2" />

    


## Resolution 
1. Before the user presses the `Post Reply` button to send message to the user, it is important to head to **Ticket Status** drop down menu from `Open`(current) to `Resolved`
   <img width="1542" height="1196" alt="Screenshot 2025-10-22 091819" src="https://github.com/user-attachments/assets/bfce3f11-3517-4cba-8328-8dad326877a2" />

2. To view tickets that have been closed, agents can navigate to `Tickets` -> `Closed` and the appropriate time frame. that this ticket is from. From here, the agent should see the completed ticket.
    
<img width="1553" height="855" alt="Screenshot 2025-10-22 092202" src="https://github.com/user-attachments/assets/c82a4d01-8a7e-4f84-a5ec-8e2663954883" />

   
   
   

   






















   

     
