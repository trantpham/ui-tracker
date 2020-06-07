# TranPham-Book

Comprises of screenshots from the book exercises

Chapter 15: <br />



Chapter 14: <br />


Chapter 13: <br />


Chapter 12: <br />


Chapter 11: <br />


Chapter 10: <br />


Chapter 9: <br />
** Functionality: In this chapter, I added a few UI functionalities to the website. The first functionality is the dropdown navigation bar that filter the status of all the bugs that were logged. The second one is the navigation bar on the top, in order to distinguish the report and the issue list. Then, I replaced all the <a> tags with <Link to> for the internal url and added some flare to the background color of the text in the index file. Lastly, the site also now has the browser history router to follow the paths of the URLs.<br />

** Challenges: This section is also fairly easy for me to follow the concepts, since the functionalities were divided into section, so it is easier to follow the author's thoughts and changes. The struggle I had for this chapter is working with dependencies, and the parsing of the graphql query when using graphql version 14.6.0. The professor was helping me with figuring out the syntax to modify the code slightly, and parse the id string as int, like how it's supposed to be. <br /><br />


![Chapter 9 Screenshot:](https://github.ccs.neu.edu/NEU-CS5610-SU20/TranPham-Book/blob/master/Screenshot/chapter%209%20screenshot.png)


Chapter 8: <br />

** Functionality: If chapter 7 is design following the architecture design and splitting into api and ui, then chapter 8 is focusing on a lot of reorganization of the files, splitting things up for better tracing in the future. It is basically split out each of the functions in api and ui into different files, and all that files as needed. The UI uses Webpack to determine application’s dependent modules and third party library dependencies

** Challenges: This chapter is fairly easy to follow in terms of concept, however, the book code snippets are written in a way that is very difficult to follow in terms of what needs to be cut out. I spent a lof of time troubleshooting and finding typos, things that got left out that the book didnt' show, but was crucial to reorganize. 

![Chapter 8 Screenshot:](https://github.ccs.neu.edu/NEU-CS5610-SU20/TranPham-Book/blob/master/Screenshot/chapter%208%20screenshot.png)


Chapter 7: <br />

** Functionality: This chapter focuses on the architecture side of the app, reorganizing all the files that I've done in the past and splitting them to API and UI side. This also allows my app to run on multiple environment, having the UI server port and the API endpoint to call. We also then have ESLint, which checks for any codes that are potentially bugs, and check if the written codes follow the standard convention. ESLint is installed for both the API and the frontend--UI.<br /> 

** Challenges: I've ran into a lot of different issues in this chapter. Some of them are due to the edit and remove code to another files, the book is pretty unclear and it took so much time to trace back the errors. Then, after able to fix the files, I had issues on file dependency on the api side, and had to re-install node.js. Then, it's just the matter of fixing small errors and make sure the server connects on the UI side to run on localhost. 

![Chapter 7 Screenshot:](https://github.ccs.neu.edu/NEU-CS5610-SU20/TranPham-Book/blob/master/Screenshot/Chapter%207%20screenshot.png)



Chapter 6: <br />

** Functionality: This chapter, the focus is mainly on understanding and utilizing MongoDB. The website is now linked the Mongo database and store any user information in it. The database allows CRUD: Create/Read/Update/Delete capability for data and information. The app has trymongo.js and a schema to init the mongo database. Then, whenever we want to add new database, we can just use the insert command in the mongo shell. <br /> 
** Challenges: I had a lot of issues related to installing Mongo and utilizing Mongo making sure that it runs properly on my Windows computer. The book is very unclear in steps of utilizing MongoDB, what and how to use it. Installilng is fairly easy, but information on troubleshooting for Windows are very unclear. Additionally, there's a lot of solutions available online for Mac users, but for Windows, it's a bit unclear and has to do a lot of digging and playing around to figure out the problem. It'd be nice for the book to address how to tackle MongoDB issues on Windows. Other than that, utilizing MongoDB and syntax is fairly easy. 
![Chapter 6 Screenshot:](https://github.ccs.neu.edu/NEU-CS5610-SU20/TranPham-Book/blob/master/Screenshot/Chapter%206%20screenshot.png)




Chapter 5: <br />
** Functionality: while we were introduced both concepts: REST and GraphQL, the book proceed with introducing the GraphQL libraries and tools for us to use in order to build the issue tracker tool. We now have a ListAPI that needed to intergrated into the UI. In order to do that, we need to make asynchronous API calls (Ajax calls). Afterwards, we converted the date/time appearance on the web by using scalar for the conversion--the the time will appear correctly according to timezones. Finally, we're making adjustment so the input data is more flexible and doesn't have to hard code the data in.<br /> 


** Challenges: I kept running into issues with installing the proper version of graphql. It was difficult to keep track of the correct npm command and the right graphql version, and therefore the server.js keeps crashing when trying to run. Afterwards, I was able to fix the issue by fixing the json file and upgrade to the correct graphql. The other issue I ran into was difficulty of keeping track of the right syntax from the graphQL, utilizing single quotes and double quotes, as well as spacing in the syntax.<br /> <br /> 

![Chapter 5 Screenshot:](https://github.ccs.neu.edu/NEU-CS5610-SU20/TranPham-Book/blob/master/Screenshot/Chapter%205%20screenshot.png)






Chapter 4:<br /><br /> 
** Functionality: For this section, I was able to handle event by using bind() and a handleSubmit() functionthis, allowing users to add their own log, instead of just showing static log like before. Additionally, this event handle can happen due to the async state initialization. allowing user to update a log, and showcase it in the table. <br />
** Challenges: I didn't have much technical difficulties for this section, most of the issues were due to typos or missing brakets, which were easy fixes. I'm still not getting used to the way the book is written. I found myself hard to follow, had to scroll to see the entire code in order to visual, then come back to that specific section to further understand what they mean. So in general, it's just a bit interrupted in terms of reading flow and thinking process. <br /> <br /> 
![Chapter 4 Screenshot:](https://github.ccs.neu.edu/NEU-CS5610-SU20/TranPham-Book/blob/master/Screenshot/Chapter%204%20screenshot.png)



Chapter 3:<br /><br /> 
** Functionality: For Chapter 3, I was able to build a website that tracks issues, similarly to JIRA, using React Components. The data is also able to pass to the children and create the nested element. <br />
** Challenges: The book didn’t clearly explain when to use JavaScript, and when to use HTML/CSS—so I have to look up and gain high level background information on when to use each of the language. I’m also still trying to get comfortable with learning how to use the port and the commands for gitBash.<br /><br /> 


![Chapter 3 Screenshot:](https://github.ccs.neu.edu/NEU-CS5610-SU20/TranPham-Book/blob/master/Screenshot/Chapter%203%20screenshot.png)



Chapter 2: <br /><br /> 
** Functionality: the "Hello World" I implemented following the book able to translate and run the code in older browser, like Internet Explorer 11 using Babel. This helps transfer JFX to JavaScript. The website is also able to send the file to m y local server. I also used Express and Node.js <br />
** Challenges: When I was working on the files, it was a bit difficult to follow which folder individual files are supposed to be in. The other challenge I have is trying to remember the steps and the process for future implementation. <br /><br /> 
![Chapter 2 Screenshot:](https://github.ccs.neu.edu/NEU-CS5610-SU20/TranPham-Book/blob/master/Screenshot/Chapter%202%20screenshot.png)

