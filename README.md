# C-Sharp-Project

This project was to contribute to the development of a website for a Theatre Company. [google](google.com)


1.      One of my tasks was to create a page where the admin can publish blog posts for all users to see.
        I created a model called News with various properties and its associated controller. 
        I used a Javascript library called Summernote as my text editor. 
        Some features include: 
        - an admin can create a post consisting of a headline and some content
        - edit, hide from view, delete functions
        - a post can be saved (not shown to the user) or published (shown to the user) 
        - sorted by PublishedDate or LastSaveDate depending on user role
        - content can include images and database will preserve HTML styling

        [Model code](https://github.com/sepan314/C-Sharp-.NET-Code/blob/master/NewsModel.cs) [Controller code](https://github.com/sepan314/C-Sharp-.NET-Code/blob/master/NewsController.cs) [Front End code](https://github.com/sepan314/C-Sharp-.NET-Code/blob/master/NewsHTML.cshtml)


2.      Another of my tasks was to create a simple messaging system between admin and user.
        I created a model called Messages with various properties and its associated controller. 
        Some features include:
        - an inbox and a sent box
        - tracks if a message is read or unread
        - compose/reply/delete message functions
        
        [Model code](https://github.com/sepan314/C-Sharp-.NET-Code/blob/master/MsgModel.cs) [Controller code](https://github.com/sepan314/C-Sharp-.NET-Code/blob/master/MsgController.cs) [Front End code](https://github.com/sepan314/C-Sharp-.NET-Code/blob/master/MsgHTML.cshtml)


3.      A third task was to add a calendar (FullCalendar) to one of the pages. 
        This calendar displays production events, filterable by search (of production names).
        Some UI features:
        - selecting an event also highlights the production
        
        [Front End code](https://github.com/sepan314/C-Sharp-.NET-Code/blob/master/CalendarHTML.cshtml)
