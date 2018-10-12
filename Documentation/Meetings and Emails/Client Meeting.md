# On Friday 5th oct 2018 I(Anurag) and Sreelekha had a client meeting with Dr. Hoot and he has suggested following changes in the presence of Dr.Case.

## General Mentor comments

1. Excellent bulleted list. Outstanding work by your team!
1. Please number items so we can refer to them easily. 
1. Which user stories are you presenting?  Be sure to follow the plan. 
1. Where are the UI sketches?  We must show sketches and get feedback before we begin doing sceens.  
1. Next week, show client/mentor UI sketches for each MVP 2 required screen. Incorporate current comments.

## Client comments (with mentor review)

1. 'Password doesn’t match' needs to be paraphrased. "Passwords do not match."
1. 'User is not register' also needs to be paraphrased "User is not registered."
1. Make sure not to give any reason for the login failure - we will remove this later, after we confirm the process is working. Add to  GDP2 requirements. 
1. Make a cw icon which represents codeword - yes - and replace in the upper left corner of the navbar. Add a new user story to MVP 3{?). 
1. Add a + button to add a course 
1. Warning screen should stay bit longer - how long? add this requirement and your delay in seconds to the user story. 
1. Instructor ability to create a course needs to be added.  Yes - but is not a part of our current MVP
1. Email address should not be case sensitive - true
1. Logout should be easy without going through many steps - add an "exit door" icon to the top level navbar (MVP 3?)
1. There should be an icon for logout - yes - see above.
1. Need to add a search icon - NEW FUNCTIONALITY - need to add a GDP 2 user story. Talk to client - and get more details
1. In student Interface, Create or delete codeword set should be removed - true - where is our sketch of the student view?
1. It is not auto filling the details like email ID - NEW NON-CRITCAL FUNCTIONALITY - if client wants autofill, please add user story to GDP 2.
1. CRN needs to be removed - true. CRN is not in any user story. Use our sample data - where is our sketch of the instructor view?

# We had a Client meeting on Oct, 10th with Dr. hoot along with me(Ujjawal), Anurag, Naveen Nuggu and Sravya and we demonstrated our app. Following was his suggestions after viewing everything meticulously:

## Client comments (with mentor review

1.	Application must be light weight. So using image and storing it might slow the application. true - there are no images in the user stories - remove this functionality. If client wants it, add the associated user stories to GDP 2 - do not incorporate un-specified functionality this semester. 
1.	Think about the impact on performance if we store the images. 
1.	Talk with mentor, whether to add images/icons or not. It also may be expensive w.r.t space. Where is the paper sketch you must review with your client/mentor first? Remove images - this is not part of your specification. 
1.	If using images/icons, it must fit and look perfectly (responsive) in mobile screen. DELETE all references to this new volunteer functionality - as a boss, I don't like paying for work that I've not hired you to do. No one can chargedfor any of this iamges work - it's costing lots of money just for the additional time it takes to review and delete un-requested features. 
1.	In mobile screen, Instructor is not able to view more than one courses in a single page. That is correct. Once course per screen is about enough.  You'll typically only have 3-5 active courses - easy to scroll through. Showing all the content required according to the user stories as they are for MVP 2 and MVP 3 are likely to take this much space. Team - proceed with the plan given. Modifications are non-critical and should be added to GDP 2. 
1.	Current design looks good on large screen and bad on small screen - Being Mobile ready is a requirement. Remove images & scale text accordingly. 
1.	Images/icons are not important things, crucial things are that Instructor’s should be able to view Name and Course and Percentage of students retrieved the code.  SEE user stories for all information that must be displayed in the course panel. 
1.	Start date is not required for the course.  Yes - and is defaulted to today. Changes to the course panel are non-critical and can be removed in GDP2. We need them to confirm critical functionality this semester. 
1.	End date of course is not required if the courses would be displayed in an order. Yes - and we want to see it to verify defaulting. Changes to the course panel are non-critical and can be removed in GDP2. We need them to confirm critical functionality this semester. 
1.	CRN needs to be removed(Not part of specification) -  team: you must follow the user stories and use our sample data. Add creative ideas to GDP 2 for discussion only. 
1.	Section should be unique with the semester.  Team: Read the user stories. There is no Semseter / Section / CRN - each course gets one unique string called "Course name" to identify it. We do not have term/semeester/section/crn - we have only a single, unique string. 
1.	There should be a unique identifier for Instructor. He/she should be able to view Course Name, Semester and Instructor’s identifier(Identifier should be randomly generated)  WHAT??  Instructors are uniquely identified by email.  They get an email (the ID) and a single name field (just like all users).  There is nothing about a randomly-generated identifier in our user stories for this semester. Whatever this refers to is a discussion for GDP 2. 
1.	There should be some default data which can be changed later like start date can be filled with today’s date (system date) and Instructor can change the data later on.  Yes - see our user stories. 
1.	Instructor’s Name is required while creating add course in course details.  Why is this critical?  It is not in our current user stories and should be deferred to GDP 2. 
1.	There must be two survey URL, pre and post. Currently there is only one URL which should not be default and should not force Instructor to use that URL only(Instructor should have access to change the URL) - Correct. Our user stories require displaying 2 urls. Please add them to our sample data.  Create/Edit functionality will come later - where are our paper sketches? 
1.	Start and End date should be viewed by both Instructor and Students but after end date, Instructor should still be able to view the dates which students cannot see after the end date. There is currently no requirement for students to view start and end date - only click to view code work.  Please work with your client to add a users story to GDP 2 to update the view to show start & end for their active courses, if this is required. 
1.	There should be some kind of checkbox to indicate show courses that are expired. This semester, our user stories have use show only active courses.  However, to fully test functionality, I agree we should show them all - please add a calculated field "IsExpired" to each course. Do not store this - calculate it by comparing today's date with the start & end. 
1.	The view should look OK in both portrait as well as in landscape mode.  Resonably so. It's a pretty good expectation that this app, like most non-video/gaming apps will be typically used in portrait mode.  If beautiful landscape mobile is desired, add to GDP 2. 

## Create Codewords - General Mentor comments

1. "Rules for creating codewords" are part of GDP 2 - use the discussions to begin building your GDP 2 requirements and user stories. 
1. This semester, record all details you can get about "rules for creating codewords" and maintain the associated user stories and requirements in your GDP 2 plan (which is due this semester). 
1. Part of the team can work on developing these requirements, but be sure to keep your focus on MVP2 and MVP3 design/sketch and development. We need to get the critical behaviors implemented fully first - and then tune appearance and additional features, etc. 

## Create Codewords Client Comments

1.	Each codeword must be different from one another by at least 2 letters and they should not be like same.  Create by hand this semester. Add inspection requirements to GDP 2 user stories and requirements. 
1.	Codewords should be 4 letters at least.
1.	Instructor should be able to know the matrix used to select the codewords.  Why? and what is this? (Not critical - move discussion to GDP 2)
1.	Instead of CLOSE button, there should be CANCEL button. It should be CANCEL and CREATE.  When we get to create/edit - which is not part of MVP2 - we need to dicuss if we will do SAVE & CANCEL or save as they type. 
1.	There should be only one way of cancelling the model. There is no need of (X) at the top right corner to cancel the model ( Talk to mentor regarding this) - Yes - come talk with me. I will ask "Which user story is this?" and "Where is the UI sketch?"
1.	Display cards for the codewords.  A list of  words is just a list of words. Why waste space putting them in a card. Regardless, tuning the display of codewords is not critical functionality - if this is a client request, add it to GDP 2 and continue building out the critical functionality. 
1.	Codewords that are approved should not be allowed to be changed and If that would be the case then what should be in the case of Instructor’s own code1.word set(He/she would be allowed to change/delete his/her own code1.word set or not? – Talk to mentor for this) - Add the desired require to user stories for "codeword set creation rules" and assign it to GDP2. 
1.	When does the assignment of codeword taking place?  We automatically and randomly assign the set of codewords to the set of emails once when the event is set up. This is the obvious and efficient approach. If an instructor deletes a student during an active course, we are fine. If they add a student and they correctly selected a codeword set with more words than students, they are fine. If a (non-forward-thinking) instructor assigns an 80-count codeword set to a course with 80 students, and tries to add one, it will violate the course creation rules as defined in our current user stories.  The (non-forward-thinking) instructor will be unable to add a student if they cannont assign them a codeword. They will have to wait til a student drops or plan better next time.
1.	Assign codeword randomly when the Course is created (At the time of creation of code1.word set – Talk to mentor for this) - Yes - we assign them not at the creation of the codeword set (codeword sets are always there), but at the creation of the instuctor's uniquely-amed course.


