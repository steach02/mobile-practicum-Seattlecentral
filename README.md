


I think we need to define a couple terms First it will help us in reading this document later.

Creator: the person who created the story currently being reviewed

User : the person who is currently using the app

Titles : pre defined text on which we will base which stories are the same or not

Story : a title that has had  a picture and other attributes attached to it

queue: holds title for future use?


Questions

Can a user tell the same story at the same time?

Can a user tell the same story with the same pictures? do we need to proof against?

Do stories contain only one picture?

How many titles are there?

Who adds new titles?

How is this done?

As of now i see know way to get to the queue screen?

the way the queue is talked about in the first slide is not consistent with that of the fourth please elaborate on what the queue should be?

will the new stories page display based on what is currently in the user’s queue?

Member profile -followers/following/stories pages seem excessive can we just combine and have icons change columns?

Functional Requirements:



General

1- all screens will direct you to the proper corresponding page

2- the different screens will be populated with appropriate data from the accompanying database

3- all data submitted will be properly stored in the database


Login screen

1- create/display facebook icon

2- User should be able to login with his Facebook 

3- Facebook icon redirects user to the home screen after login process

4- create/display google plus icon

5- User should be able to login with Google plus account

6- Google plus account icon redirects user to the home screen after login process 

7- create/display terms and conditions statement

8- href keyword Terms to redirect to app store

9- jref keyword Policy to redirect to app store 

10- User should be able to see terms and conditions on the App store

11- User should be able to review privacy and policy on the App store

12- create display logo

13- create display sign in text 


ToolBar

1- create/display “frame” icon(two hands)

2- frame icon redirects you to home screen

3- create/display “new story” icon(lightbulb)

4- new story icon redirects you to new stories screen

5- create/display “profile” icon (chair)

6- queue icon redirects you to profile screen


Navigation Bar

1- add/display back button 

2- back button should take you to previous screen

3- login only screen without navigation bar

4- add display name of current screen or user accordingly 


Home Screen

1- display picture in center of screen (card format top and bottom border)

2- screen should be scrollable

3- screen should allow for left and right swipe

3- left and right swipe will display pictures that relate to the same subject matter

4- display logo top of screen

5- top left: display user name 

6- href creator name redirect to Profile_Stories->creator

7- top right: display ellipsis icon

8- clicking ellipsis icon generates popup  

9- pop up contains five elements : Share, tell, add to queue, report and cancel

10- cancel btn closes popup with no action taken

11- report btn will send notification for review (containing the story creators information/story information)

12 report btn will remove the story from the visibility of the user who reported it

13-report btn will close popup after action is taken?

14-queue btn will check  to see if story is currently in users queue

15- if story is in queue send error msg 

16-if story is not in queue and to queue 

18- queue btn will close popup after action is taken 

19- tell btn will redirect to camera screen passing title information

20- tell btn will close popup befor redirect

21- share btn will display collection of social media options to link story to(To be expanded on at a later time)

22- bottom left: create display “like” icon(solid color)

23- send notice to creator containing who liked the story (via?)

24- increase like count

25- bottom center: create display “title” text

26- bottom right create display “comment” icon 

27- comments icon redirects to comments screen passing creator information

28- display top three recent comments-please see Reconsider-Home

29- display a view all comments-please see Reconsider-Home

30- view all redirects to comments passing creator information

31- display likes

32- scrolling up/down displays different titles from different people


New Stories Screen

1- Create/display story icons for all titles

2- when icon is selected change to tell/add icon

3- if the screen is touched outside of the tell/add icon revert back to the title icon

4- Tell icon redirects to “Camera” screen passing title information

5- add to queue icon adds title to queue 

6- add to queue icon removes that titles icon from new stories for that user

please see reconsider-New Stories

note(does the screen check the user’s queue on new titles screen load)


Queue Screen

1- screen will be scrollable

2- create/display all titles in queue as icons/btn

3- selecting icon will redirect you to camera screen passing title information

4- selection icon will remove icon from queue

5- when user swipes left on icon delete option appears

6- tapping delete option deletes title from queue refresh screen

7- when delete option tapping any where other than delete icon will revert to normal title icon

8-  top left: create display “back” icon

9-  back icon returns you to new stories scree- see Reconsider-Queue screen


Comments Screen

1- back button will take them to the previous screen

2- a comment will consist of a  creator's thumbnail picture, name, their comment, and a date time stamp

3- names and images will be hrefs to the creators “Member Profile_Stories” for that creator

4- bottom: add/display text entry box 

5- bottom: add/display send btn 

6- send button, submits comment and refresh page


Member Profile_Stories/following/followers

1- back btn return you to previous screen

2- display creators user picture 

3- navigation bar displays creator’s name

4- add/display user about blurb beneath photo

5- right of photo: add/display “follow” btn

6- user selects follow btn

if Public 

    6.1-follow btn display changes to following

    6.2- creators “followers” count increases by 1

    6.3- users “following” count increases by 1

    6.4- user name will be added to the creators “followers” list

    6.5- creator’s name will be added to the users “following” list 

if private

    6.6- follow btn display changes to pending

    6.7 send push Notification of pending follower attach user information

    6.8 user name is placed in creators pending list

7- beneath about blurb display/add followers icon

8- followers icon redirects to “Member Profile- followers screen

9- beneath followers icon add followers count

10- beneath about blurb display/add following icon

11- followers icon redirects to “Member Profile- following screen

12- beneath following icon add following count

13- beneath about blurb display/add stories text 

15- beneath stories text add stories count

16- whichever icon is being used will be indicated by a color change

For Stories(default)

17- bellow counts in two columns add/display all stories created by this creator(picture and title)

18- stories redirect to Member Stories screen 

For followers

19- display all followers names and follow btn (same functionality as previous)

20- names redirect to that person’s member profile screen

For following

21- display all followed names and follow btn (same functionality as previous)

23- names redirect to that person’s member profile screen


Members Stories Screen


this screen contains the same functionality as the home screen except for the following

1- scrolling up and down will display different stories from the same creator 

2- swiping left or right will display the same story by different creators

please refer to Reconsider-Members stories



Reconsider

-Home

    1-displaying multiple comments will make each story display seem bulky consider displaying only the number of comments 


-New Stories

    1- consider tell/add/cancel instead of an off icon cancel cleaner and more intuitive

-Queue

    1- the back button should take you to the screen which you were at before you proceeded to the queue 


-Members Stories/followers/following

    1- it seems to be overcomplicating the program by giving the users the option to swipe left at this point to see stories not associated with this creator is it necessary

    2- is having the follow btn for every follower following person necessary



