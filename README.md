# GSOC Proposal submiited under KDE for GCompris.

Name				        :Sagar Chand Agarwal
Email Id		        :atomsagar@gmail.com
Freenode IRC Nick		:sagaragarwal94
Location			      :Jaipur,India,+5.30 GMT

#####Proposal Title    : Port of GCompris in Qt Quick
#####Mentor       	    :Bruno Coudoin < bruno.coudoin@gcompris.net >
#####Co-Mentor     	  :Johnny Jazeix < jazeix@gmail.com >

###Motivation for Proposal

Currently GCompris has few activities and is mainly centered in math,fun games and mouse simulations.
Looking at the great response from  users of GCompris,I think that GCompris should include more activities which will make it more resourceful,usable and popular among young children and teachers .My main goal will be porting some more activities from its existing GTK+ version and introducing something new.
I am interested in creating a new section of Science,Environment and Computer Sciences.


###Project Goals:

At the end of the project,GCompris will contain newer three sections (Science , Environment and Computer Sciences).Under Environment,I will propose to include tree growing simulator,extending existing water cycle to oxygen cycle  and garbage selection activity. Under Sciences,I will propose to include camera simulator. Under Computer Sciences,I will like to include binary to decimal converter along with binary addition and subtraction.
Apart from creation of new activities,I will also port electricity activity and hangman.
These ported activities will have newer looks,more content and resources.
Since I will be in my college,I will display the activities in my community school and collect feedbacks from them.

###Implementation Details:

I will make use of https://openclipart.org and Inkscape to make viable vector images,use audio to add more interactivity and combine two or three activities and make it more viable .I will be regularly writing blog for my daily events and progress in the project.



###Timeline:

####Upto May 25(Porting existing activities):

I will continue to port existing activities and have a richer knowledge of GCompris .
During this,I will be in regular interaction with mentors and grasp the most of concepts.

####From May 26:

I will start by implementing tree growing simulator and there will be a panel of different elements required for nourishment of tree like soil,water,seeds,compost ,sun and cloud. An audio voice with text description will be there for smooth navigation and learning of the factors.
It will be a fun as well as learning activity for children as it includes the some benefits of gardening.

Approximate time:(10 days of development and few days for review)

An oxygen cycle,just like water cycle which will be governed by selecting different objects in the screen like plants,sun,water ,humans and homes and see the role of each object  in contributing or using oxygen.
By this activity,it explains about the importance of oxygen and also provides the inner view about the differences which nourishes oxygen in earth and the other effects which reduces level of oxygen.

Approximate Time:(7 days of development and few days of review)

A Garbage Recycle activity,under which according to difficulty levels,there will be organic,inorganic,recycle and non recyclable wastes will be there and the user has to select either of them and choose the required dustbin(on increasing levels the waste items will be increased).

Approximate Time:(10 days for development and few days for review)

Identifying the parts of computer :In this activity there will be a image of computer shown  at the screen,and the user has to place the text buttons present on the side of the screen to the correct components. There will be a audio support and text(using tooltip) too to aid the user and understand the parts.

Approximate Time:(7 days of development and few days for review)

I would like to take the idea for Camera Simulator from this link.( http://www.kamerasimulator.se/eng/  ) and port it. 
It will help the children to understand the different concepts used in photography, focal, focus, iso and aperture. We could let the children take a picture and simulate the rendering given by virtual camera settings.

Approximate Time:(10 days for development and few days for review)
	
#####I will be also porting two activities during the summers:

Electricity Activity:In this,user has to choose different components and connect them glow a bulb . Under existing activity,after being ported,the newer thing will be the inclusion of flow of direction of current and associated formula involved (like V=IR) with  series and parallel concept. I will also implement a double pole switch concept and it will be inside the electricity activity.
Since in original GTK+ activity ,it uses gnucap.In this,I will take help from the link( https://github.com/edx/edx-platform/blob/master/common/lib/xmodule/xmodule/js/src/capa/schematic.js ).Before summer,I will see the code and try to remodel it to my activity.
Approximate Time:(About 20 days of development and few more for reviews)

Hangman:Hangman is the best one .Along with porting and increasing its vocabulary is the must and this link provides us some help ( http://www.manythings.org/hmf/ ).In this activity,I will also try to include images and text,so that it becomes more interesting. 
Approximate Time:(About 10 days of development and some days for review)

####22 August to 28 August:(pencils down) 

Doing testing as whole. Encouraging other community people and users to use GCompris and to report bugs if any and getting their feedback. Fixing the posted bugs.

####After 28 August:(Continuation)

This is not the end,I will be continuously involved in the community and develop more activities into GCompris.

###Do you have other obligations from late May to early August (school, work, etc.)?

My college exam will be ended by first week of May.I will be completely free from May 2 to first week of August,because of summer vacations.I have no obligations or any internship offers.After first week,I will be able to commit 6 hours from Monday to Friday and on weekdays,I will be completely free.

###About Me:

I am a student currently in second year,pursuing Bachelor of Technology course with Computer and Communication Technology as major in The LNM Institute of Information Technology,Jaipur,India.

Apart from academics,I have great interest in Free Software.I am also a Firefox Student Ambassador and Firefox Club Lead at my college.I have attended seminars and conferences related to like Mozilla Hive,MCR Wingdings and conf.kde.in (It was my first Open Source event in 2014).

On the community part,I am a follower and contributor of Mozilla Firefox Os. As Firefox Ambassador,I conduct coding sessions(like introduction to Github , Webmaker and Appmaker )in my college .I have been using GNU / Linux from last two years, and KDE since last 5 months. GCompris concept and its ideas matching to my own thinking helped me to code my first activity rainbow ( https://github.com/bdoin/GCompris-qt/pull/74 )and worked on existing activity watercycle( https://github.com/bdoin/GCompris-qt/pull/75 ) .

Given a chance to work on this project, I assure dedication of at least 40 hours per week to the work and that I do not have any other obligations during the period of the program .I plan to actively maintain my code and help developing in GCompris  even after my GSOC time period is over.

###Why am I apt for the project:

Familiar with QtQuick Concepts and also am familiar with coding style of GCompris.
I love to code(been coding for past 2 years) and have been taking part in my college coding competitions and projects.
Love to do activities which are concerned to children alongside the standards of open source.
