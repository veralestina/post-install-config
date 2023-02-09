<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Objective 1: Learn what each Role does; how does it differ from Agent? 
- 
- Objective 2: Learn how different Departments work different cases and how the ticketing system is set up for that.
- 
- Objective 3: Learn how to configure Teams and how in the work place teams are used.
- 
- Objective 4: Learn how people create tickets.
- 
- Objective 5: Create new Agents and assign them different Roles and to different departments.
- 
- Objective 6: Create users who will be creating tickets.
- 
- Objective 7: Create the SLA's - Service Level Agreement. This is the companies policy for what tickets get worked first and how they get sorted based on severity impact to the company.
- 
- Objective 8: Using the SLA, create the Help Topics for the tickets.


<h2>Configuration Steps</h2>

- In our newly created OSTicket site, we login to the adminuser

<p>
<img src="https://github.com/veralestina/Images/blob/main/Github%20information/useradminloginosticket.png" height="40%" width="40%" alt="adminuserlogin"/>
</p>

- We open to the Admin Panel and click Agents, and then click Roles. In Roles, we set our adminuser as Supreme Admin. The Supreme Admin gives us the ability to create Roles for other users and assign other users to Teams, and different Departments.
- Next we go to the Departments tab, where we click on System Administrators. We set up the System Admin.
- We go to Teams and create two teams - IT Team 1 and IT Team 2. IT Team 1 will be used for Level 1 support and IT Team 2 will be used for Level 2 support.
- Create new agents; go back to Admin Panel, then click Agents and then click the Add New button. Create at least 2 new agents.

<p>
<img src="https://github.com/veralestina/Images/blob/main/Github%20information/osticketaccess.png" height="40%" width="40%" alt="newagent"/>
</p>

- Create new users; go back to the Admin Panel, click Users and then click the Add New button. Create at least 2 new Users. Give them the ability to create tikets by clicking Settings. Make sure they need to require a login username and password to be able to create a ticket request.

<p>
<img src="https://github.com/veralestina/Images/blob/main/Github%20information/osticketsettings.png" height="40%" width="40%" alt="usersettings"/>
</p>

- Create the SLA - Service Level Agreement. This is how the tickets will be sorted based on the severity of impact on being able to continue working and how the issue impacts the business' bottomline. Our SLA is SEV-A(1 hour, 24/7), SEV-B(4 hours, 24/7), SEV C (8 hours, business hours) SEV-A is high importance, and these tickets are prioritized and need to addressed and completed within 1 hour and that they need to be addressed 24/7, not just during working business hours. SEV-B is important and needs to be addressed and completed within 4 hours of the ticket being created and the issues need to be addressed 24/7, not just during working business hours. SEV-C are least important and need to be addressed and completed within 8 hours of the ticket being created but they only need to be worked on during business hours.
- Now we configure the Help Topics. We go back to the Admin Panel, go to Manage and click Help Topics. We create the topics Business Critical Outage, Personal Computer Issues, Equipment Request and Password Reset. These are topics that Users can choose based on their ticket request need.

We have successfuly created the Users who will request tickets and the Admins who will work the ticket requests based on the SLA that we have created for our IT support team.
