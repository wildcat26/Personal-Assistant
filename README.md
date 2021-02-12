# Personal Assistant to the Working Professional

This web-based functional prototype is a part of Microsoft's Engage WIT 
Hackathon.



## High Level Design
The application works on a server-client architecture with one web server and one database server**. Requests and responses are exchanged with the frontend of the application by the web server. The web server also interacts with the database server to reflect the operations performed by the user. 

Since this is a functional prototype intended to be a proof-of-concept, one database server and one web server would suffice. To make the architecture scalable, a cluster of web servers would be needed to respond to the enormous number of requests being received.

Several database servers would ensure that user data is frequently backed-up. A hot backup can also be created.

![](https://i.imgur.com/HzCWsP7.png)

## Tech Stack chosen

### Frontend
React.js

### Backend
Node.js

### Database** 
MariaDB, an open-source SQL-based RDBMS

**to be integrated with the frontend in future versions
Currently, dummy data is shipped with the frontend.



## Implemented Features
1. A ToDo list with 3 categories - Tasks, Follow-up, Meetings
2. Dashboard with count of total, completed and in-progress tasks
3. Charts for plotting count of active hours, total and completed tasks over a week
4. A Leaderboard where the user can see how she/he ranks amongst her/his friends in terms of the number of active hours.
5. A User Profile section
6. Events section with a date-time picker to add time to certain tasks, ex: meetings, deadlines.***

*** incomplete

## Other Desirable and Useful Features
1. User authentication
2. Calendar to schedule meetings, view all meetings on the Calendar in the front end
3. Todo list with reminders. Notifications for approaching deadlines.
4. Status of a user - Active, DND, Invisible, On a quick coffee break, In a meeting
5. Adding friends to enable the leaderboard feature to work, viewing their status (can be colleagues)
6. Pomodoro timer in the app to enhance the user's productivity. Rewards to be given on the basis of successful Pomodoro cycles completed
7. Analytics on the basis of status of a user - to provide the user their most/least productive times of the day
8. Third-party integrations with Video Conferencing and email clients to see meetings scheduled, emails in the app


## Credits
- Copyright 2020 Creative Tim (https://www.creative-tim.com) licensed under MIT (https://github.com/creativetimofficial/material-dashboard-react/blob/master/LICENSE.md)
- Image credits - https://reinvently.com/blog/fundamentals-web-application-architecture/

## Useful Links

Deployed React application: https://wildcat26.github.io/Personal-Assistant

Do note that refreshing the page after it is rendered will cause a 404 Page Not Found error since https://wildcat26.github.io/Personal-Assistant routes to https://wildcat26.github.io/admin/dashboard, not vice versa.

Demo Video:

