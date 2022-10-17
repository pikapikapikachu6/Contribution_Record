# Lavender Individual Report (week9 - week10)

## A clear statement of work done

### Summary of Work Done 
- **Brief Summary of XP roles**  

| Week | Work Planned |
|----------|:-------------:|
| week 9 | Bitbucket Expert |
| week 10 | Report writer |

- **Technical tasks and roles**  
    - **week 9**   
        In week 9, my role was that of a Bitbucket expert, and to avoid code conflicts, I created a new branch in Bitbucket and submitted my code for the "like" function. As the project team member, I set up the project unit testing environment.

    - **week 10**  
        In week 10, my role was that of report writer, and I assembled and worked with my teammates to complete the week11 progressive report. As a team member, I completed the first round of functional testing, testing a total of 55 test cases, passing 33 and failing 22. The reason for this was that our development was not complete and some of our code had not been code reviewed and therefore had not been merged into the master branch. Also I tried to write unit testing but failed.

- **Other responsibilities**
    - **week 9**  
        In week 9, my role was that of Bitbucket expert, and I followed the Bitbucket commit process to make sure our project had no code merge conflicts. I participated in a tutorial class on Tuesday, where we worked on code review and merging. And I supervised the person in charge to finish the wiki for week 9.

    - **week 10**   
        In week 10, my role was that of report writer, I finished the week11 progressive report together with group members. And I generated a test report including the first functional testing test cases including each test case's name, testing steps, the result and so on. As a team member, I researched how to write XCtest.

### Weekly Plan
| Week | Work Planned | Work Completed |
|----------|:-------------|:------|
| week 5 | <li> Plan to monitor Bitbucket process. <li> Plan to finish and submit the “like” function. | <li> Monitored Bitbucket process and ensured there is no merge conflict. <li> Finished and submitted the “like” function. <li> Setup the project unit testing environment.|
| week 6 | <li> Plan to write progressive report. <li> Plan to do functional testing. | <li> Finished progressive report. <li> Finished the first time functional testing. <li> Generated the first testing report for functional testing. <li> Researched on how to write XCtest. <li> Tried to write unit testing. |

## The extent of the work
### week 9
As a bitbucket expert, in week 9 I oversaw the processing of commits and avoided merge conflicts. We merged a total of two times. Once on Monday of week 9, the last day of the midterm break, and the second time on Tuesday during tutoring session and before the client meeting. We merged the code we wrote over the holidays. I was the bitbucket expert to make sure there were no conflicts.  
[*Bitbucket_commit:*]   
![Bitbucket_commit](./week9/commit.png)  

As part of the project team, I completed and committed the code for the "like" feature. As a Bitbucket expert, I chose to create a new branch and then commit the code in the new branch to avoid code conflicts.  
[*My_commit:*]   
![My_commit](./week9/like.png)  

As a Bitbucket expert, I made sure that our week 9 wiki was complete and that the roles of the project members were correct.  
[*Wiki:*]   
![Wiki](./week9/wiki.png)  

As part of the project team, I set up the unit testing environment. First I chose a new target belonging to the “Unit Testing Bundle”, and then I initiated the parameters for our project.
[*Unit_testing:*]   
![Unit_testing:](./week9/unit_testing.png)  

### week 10
As the report writer, I assembled and worked with the rest of the project team to complete the week11 progressive report.
[*Progressive_report:*]   
![Progressive_report:](./week10/progressive.png)  

As a group team member, in the ninth week, I did the first functional test, because our project was modified during the actual development process and the original design, so I first cut our use case before testing and Edit, in the end, I actually tested 55 test cases, 33 passed, and still 22 are currently showing results that are not as expected, because our development is not complete, and there is a part of the code that has not been merged into the master branch.
[*Test_report:*]   
![Test_report:](./week10/test.png)  
Here are the raw file:  
[P52-Recipe Recommendation and Diet Management based on Selected Food.-first function test-Case.html](./week10/P52-Recipe%20Recommendation%20and%20Diet%20Management%20based%20on%20Selected%20Food.-first%20function%20test-Case.html)  
Or  
[P52-Recipe Recommendation and Diet Management based on Selected Food.-first function test-Case.csv](./week10/test.csv)  

[*Test_report_summary:*]   
![Test_report_summary:](./week10/report.png)  

[*Test_report_graph:*]   
![Test_report_graph:](./week10/graph.png)  

As the project team, I researched a lot about how to do the unit testing and UI testing using the XCtest.
[*Research:*]   
![Research:](./week10/research.png)  

As part of the project team, I tried to write the unit testing for our project. But I failed in the import module, it always told me that “no such module..”. I researched a lot but still now haven’t handled this problem. 
[*Unit_testing:*]   
![Unit_testing:](./week10/unit_testing.png)  
[*Research_bug:*]   
![Research_bug:](./week10/no_module.png)  

## Quality of technical work done
The Zentao platform ensures the quality of our functional tests. During these two weeks, I used this platform to complete the first functional tests for our project. I have written test cases according to our pre-development design before development. During the actual development process, we changed some designs according to the actual situation and customer's requirement changes. The current progress of our project is that we are about to finish the development. In week 10, I changed or removed some test cases based on the current design of our application. Then I added some more test cases according to the latest expectations.After fixing the test cases, I executed them one by one according to the current development results and recorded the corresponding test results.The advantage of using the Zentao platform is that the results of executing a test case can be recorded in detail, and if it fails, I will choose to record the current results next to the corresponding step. After all test cases are executed, I export all test cases and generate a test report. In this way, each functional test can be well recorded, which is convenient for us to carry out regression testing, and also helps the whole project and the client understand the quality of our tests.  
[*Test_report:*]   
![Test_report:](./other/test.png)    

[*Test_report_summary:*]   
![Test_report_summary:](./other/report.png)  

[*Test_report_graph:*]   
![Test_report_graph:](./other/graph.png)  

[*Test_fail:*]   
![Test_fail:](./other/fail.png)  


## Other contributions to group processes
I contributed to attending meetings every time. I have not missed a group meeting or meeting with a client. And I contributed to recording feedback from every meeting with clients.   
[*feedback*]    
![feedback](./other/feedback.png)

I contributed to completing assigned tasks on time and responding to messages promptly. For example, I was assigned to send an email to the client, then I will finish immediately. And when other members need some, I will reply and provide quickly.
[*on_time*]    
![on_time](./other/ontime_assigned.png)

[*on_time*]    
![on_time](./other/ontime_finished.png)

I contributed to using my experience to help our project in the testing part. I have some software testing experience before but they are not iOS application related. Thus, I also need to do some research on iOS testing. But compared to our group members, I may be more familiar with the testing, then in group report, presentations, I did the testing part. And I was assigned the XP roles as the tester more frequently. 
[*group_contract*]    
![group_contract](./other/contract.png)


