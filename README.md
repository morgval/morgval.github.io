```
Hello World. 
My name is...
```
# Morgana Val.
### I love experimenting with new technologies!

[Self Assessment](#self-assessment) | [Code Review](#code-review) | [Projects](#projects) 

## Self Assessment

Two months ago, it finally dawned on me, "I am really finishing my computer science degree." I did doubt myself for awhile that I could ever prove to be a programmer, but I was also shooting too high for having just come into this a little over two years ago.  I had dreams of working with artificial intelligence and cybersecurity, when I barely knew how the internet worked.  The Computer Science program definitely taught me that we all have to have humble beginnings. There are a few main skills I have acquired during my time that pertain to the tech industry:

### Collaborating and Communicating with a team and stakeholders
Much of my coursework required reading, understanding, and participating in mock Agile events to understand the software development lifecycle.  I learned the different types of documentation and presentation methods to use when relaying information to stakeholders.  Version control technologies like GitHub are important for collaborating with team members so work is not overwritten and feature releases can be tracked appropriately.  The [student records project](#projecttwo:-student-records-web-keeper) and the documentation I go over in the [code review](#code-review) are the best representations of this skill in my portfolio.

### Data Structures and Algorithms
The first programming language I learned was Python but I have just as much experience working with data structures and algorithms in Java.  Although I don't have portfolio pieces for Java, I created the [student records project](#projecttwo:-student-records-web-keeper) in JavaScript because I felt my experience with Java would make it easier.  I had no problem solving problems but overall the languages were very different. In the [MongoDB project](#projectone:-grazioso-salvare-database-dashboard), I explored Python more and had the opportunitiy to learn a few frameworks, like Dash and PyMongo.  

### Software Engineering
Aside from the database project, I had never created a piece of code as extensive as the student records project.  I wanted to explore DOM manipulation by building my own version of a database using Javascript and Bootstrap.  I had a lot of goals for this project and will probably continue to work on this as I continue to acquire new skills and technologies.  At this point you can view the minimum viable product (MVP) developed so far [below](#projecttwo:-student-records-web-keeper).  Both of the below projects gave me experience working with interfaces, which was fascinating for me as I have experience in graphic design so user experience and design with very important to me.  

### Database Management and Security
In addition to the [Grazioso Salvare Dashboard](#projectone:-grazioso-salvare-database-dashboard), I have worked with MySQL and relational databases in past coureswork and plan to implement some of that into my portfolio when I can expand it into appropriate projects.  I also plan to include a data mining project, one of the projects I am most proud of, where we used JMP to create graphs to analyze big data for the purposes of making decisions for an organization.  The database project below gave me experience with RestAPI, NoSQL, and MongoDB, so I can look forward to learning more about scalable database architectures.

## Code Review
As a part of the completion of my degree program, I needed to select one to three projects that best represent my skills and proved I have learned the core computer science concepts over the past two years.  I unfortunately did not have access to the complete extent of my degree projects (my desktop computer is stored as I am moving) but I chose two projects that showed my ability to work with new technologies and understand the frameworks already establsihed.  This final project also required me to perform a code review before making modifications.  There were five course outcomes I had to prove my knowledge of the computer science field, and the code review fulfills the second and fifth:

> {CS-499-02} Design, develop, and deliver professional-quality oral, written, and visual communications that are coherent, technically sound,
and appropriately adapted to specific audiences and contexts <br/>
> {CS-499-05} Develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities,
mitigate design flaws, and ensure privacy and enhanced security of data and resources 

[![CS499 Code Review](Portfolio Code Review Thumbnail.png)](https://www.loom.com/share/58fb4ee2a6bd4f29b211d4e682f31f07?sharedAppSource=personal_library "CS499 Github Pages Portfolio Code Review")


## Projects
### projectOne: Grazioso Salvare Database Dashboard 
[<img height="20" width="20" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/python.svg" />](python.org)  [<img height="20" width="20" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/mongodb.svg" />](mongodb.com)  [<img height="20" width="20" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/json.svg" />](https://www.json.org)  [<img height="20" width="20" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/numpy.svg" />](numpy.org) 
 [<img height="20" width="20" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/pandas.svg" />](pandas.pydata.org)  [<img height="20" width="20" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/plotly.svg" />](plotly.com/dash/)<br/>   


[![projectOne Repository Card](https://github-readme-stats.vercel.app/api/pin/?username=morgval&repo=GS-Dashboard)](https://github.com/morgval/GS-Dashboard)

The GSDB Dashboard project consisted of two parts; there was a program to create, read, update, and delete records from their MongoDB database and that program's test module, and a browser based dashboard to view a datatable that displayed records based off of certain search parameters and a chart and map to sort those records.  I created it during CS340: Advanced Programming Concepts.  However, during this course, CS499, I revised a few algorithms to make the charts more interactive and revised the map feature to work as originally intended, but not executed.  My biggest challenge with this artifact has consistently been that I keep shooting too high. I really wanted this to work properly through Jupyter, but I wasn't able to find a proper tutorial on it until recently, so here is what I still want to polish off:

- [ ] Revise JupyterDash module to work on GitHub
- [ ] Revise README

This project helped me fulfill three course outcomes:

> {CS-499-01} Employ strategies for building collaborative environments that enable diverse audiences to support organizational decision
making in the field of computer science <br/>
> {CS-499-03} Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and
standards appropriate to its solution, while managing the trade-offs involved in design choices (data structures and algorithms) <br/>
> {CS-499-04} Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of
implementing computer solutions that deliver value and accomplish industry-specific goals (software engineering/design/database) 

Using the technologies linked above, I learned to consider an organization's needs regarding data and how they use data to make decisions. It was one thing when I took my database course and learned about how the RDBMS interacted with the server that held the memory to run the information for the user application, but it was entirely different to actually develop one.  Developing a CRUD module for database management and then a dashboard to filter and present information gave me much more confidence to take on learning new web technologies.  In addition, I learned about RestAPI, the software architectural style that has come to define much of the internet today.  As I delve deeper into databases and cloud technologies, I have a feeling this introduction to the concept will come in handy.  I became familiar with the JSON as well and would like to create a version of the next project that runs to manipulate JSON objects, not just DOM elements.

### projectTwo: Student Records Web Keeper
[<img height="20" width="20" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/html5.svg" />](https://developer.mozilla.org/en-US/docs/Web/HTML)  [<img height="20" width="20" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/javascript.svg" />](javascript.com)  [<img height="20" width="20" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/bootstrap.svg" />](getbootstrap.com)  [<img height="20" width="20" src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/jquery.svg" />](jquery.com)<br/>   


[![projectTwo Repository Card](https://github-readme-stats.vercel.app/api/pin/?username=morgval&repo=Student-Records-Dashboard)](https://github.com/morgval/Student-Records-Dashboard)

The Student Records project helped me solidify my understanding in the same three course outcomes as the GS-Dashboard. Basically, the program keeps student and class records to register students to courses.  During this course, I implemented a few different algorithms into a [Javascript CRUD tutorial](https://youtu.be/-rNQeJi3Wp4) I found on YouTube to expanded the functionality of the tables established.  I was able to make it so a student could be registered to a course; the user would selected the class record, click register, enter the Student ID, click register again and could return to the student tab to see the student record's class roster populated.  I also implemented the following algorithm to restrict students with a GPA too low to only be able to register to 3 classes:

```javascript
//logic for validating a student has the ability to register
       var gpa = document.getElementById(selectedStudent + "-gpa").value; //get GPA data for student (in fourth column)
       var table = document.getElementById(selectedStudent + "-classRoster");
       var numClasses = table.length;
       var tbody = table.getElementsByTagName('tbody')[0];
       if (gpa < 3.0 && numClasses >= 3) {
           return (alert('Cannot register student.  GPA requirement not met.'))
       } else {
           //placing class row data in the student's class roster table
```

It isn't exactly scalable, but it does some of the basic functions of a database. This project began in IT315: Object Oriented Analysis, where we used the Agile development lifecycle to plan the use cases prior to development.  These use cases then became the basis for testing the development. I wanted to implement classes to represent the objects in this project but was unable to get the project to function properly that way.  I was disappointed I wasn't able to accomplish all I had originally thought because of the unexpected bugs I hit, but I learned a lot about problem solving and am now very excited to call this my MVP (minimum viable product).  It has the basic features, and it works but it has bugs and lots of room for improvement as I progress as a programmer.   I would also like to look into:

- [ ] implementing React
- [ ] optimiziing the compilation time
- [ ] adding a Student Roster setting in the Class table
- [ ] expanding Date() capabilities and add per-term registration requirements
