>   **SENG 438 - Software Testing, Reliability, and Quality**

**Lab. Report \#1 – Introduction to Testing and Defect Tracking**

| Group \#:       | 6 |
|-----------------|---|
| Student Names:  | Sanchit Kumar  |
|                 | Aninda Shome  |
|                 | Isaiah Asaolu |
|                 | Ibrahim Asad  |

**Table of Contents**

(When you finish writing, update the following list using right click, then
“Update Field”)

[1 Introduction	1](#_Toc439194677)

[2 High-level description of the exploratory testing plan	1](#_Toc439194678)

[3 Comparison of exploratory and manual functional testing	1](#_Toc439194679)

[4 Notes and discussion of the peer reviews of defect reports	1](#_Toc439194680)

[5 How the pair testing was managed and team work/effort was
divided	1](#_Toc439194681)

[6 Difficulties encountered, challenges overcome, and lessons
learned	1](#_Toc439194682)

[7 Comments/feedback on the lab and lab document itself	1](#_Toc439194683)

# Introduction

This report contains the results of non-scripted manual testing, scripted manual testing, and regression testing completed on an ATM simulation system created by Gordon College. The defect reports presented in this report are created and documented using Backlog. With pair testing used during the exploratory testing process, the thought process of each pair of Engineers prior to the exploratory testing is presented. The findings in this stage are then compared to manual scripted testing completed on the same system. Finally, these defect reports are peer reviewed and changed based on feedback provided by each pair. Preceding this assignment, the most any Engineers in this group knew about exploratory and manual functioning testing was what was taught during lectures. We knew that exploratory tested involved designing tests and executing them at the same time. We also knew that it was important to explore as many different options as we could think of. In lecture, we learned that manual scripted tests are designed first and recorded. After they are designed, these tests can be executed later in time by different people so that they can see if the bugs occur. 

# High-level description of the exploratory testing plan

Going into the Exploratory Testing, as a group we had decided to, at the very least, test every main function present in the system. This would mean testing all options presented, all text boxes, and all inputs that a user may enter. This was especially important in this case because we are dealing with an ATM system. Generally, systems that are concerned with dealing with money and sensitive information like credit or debit cards need to be absolutely bug proof. There should be absolutely no way for a user to enter input that would allow for the user to gain access to an account that they do not own or perform transactions that should not be possible. As a result, we wanted to particularly test whether the ATM system would securely allow for a user to use their account and perform transactions that work correctly. This would mean that each pair would test each significant function multiple times with different and unexpected inputs. 

# Comparison of exploratory and manual functional testing

In comparison to the exploratory testing, the manual functional testing is much more efficient because all the tests are laid out with all the information required to replicate the test. This saves a lot more time and gives clear instructions which allows us to finish the tests much easier. In terms of effectiveness, exploratory testing allows us to explore more variables because we go through the program thoroughly. Although a trade-off of using this testing is that it can be more time consuming than manual scripted testing which proves that manual scripted testing is much more efficient as stated earlier. A trade-off of using exploratory testing is that it relies on the experience of the tester, and if they’re more experienced then they will be able to do it much quicker, but for us, since we were just introduced to this it took a bit to get going and catch things. A huge benefit of exploratory testing is that it allows for a lot more creativity and freedom when it comes to testing things, and this can allow us to come up with more defects. Another comparison between these two testing methods is that manual functional testing is must more structured in what needs to be done, whereas exploratory has very loose structure. 

Once we completed the testing for both exploratory and manual scripted testing, we realized that the exploratory testing was much more effective for us. Out of the 19 defects we found, 16 of them were found from exploratory testing, 3 new defects were found from manual scripted testing, and 7 of the total defects were found through both testing methods. As you can see, we were able to find many more defects through the exploratory testing. If we had only done manual scripted testing, then we would only have found 10 defects and missed the 9 other defects we found through exploratory testing. In conclusion, exploratory testing allowed us to find more defects despite taking longer than the manual scripted testing.

-   Note that you need to submit a report generated by your defect tracking
    system, containing all defects recorded in the system.

# Notes and discussion of the peer reviews of defect reports
First, we split into pairs (groups of 2) and then began the exploratory testing, one person in the pair did the test, then the other person would review the test and verify. After each pair was done the exploratory tests were swapped the results between the pairs and then verified and confirmed each others’ defects. One thing we found was that there was a lot of similarity between the defects each pair found. Furthermore, since we split up into pairs, we were able to cover more ground. Each pair ended up finding some smaller bugs that the other pair had not noticed, and thus our list of bugs grew, and we were able to create an extensive list of the existing bugs.  

# How the pair testing was managed and team work/effort was divided 

We first organized a time for everyone to meet up, and then we chose to separate into groups of two, Sanchit and Aninda, and Isaiah and Ibrahim. Within the groups, one person would do the testing, and the other would record the bug and suggest ideas to test. Once this was done, we arranged another time to meet up, and then we discussed our findings by sharing it in a table form on a google docs. We then reviewed the tables together and found some similarities in the defects we had found. 
Once the exploratory testing was finished, we divided the work for the manual scripted testing evenly amongst the four of us. Since there were 40 manual scripted tests, we gave each person 10 tests to do. While doing these tests, we recorded the ones that failed onto our google docs. Once everyone completed their tests, we looked for defects that were found in these tests that we also found in our exploratory tests. We then took the new defects which we had not found before and put them in backlog. 
In the last step, for regression testing, each of us checked the defects we had put on backlog on the new version of the system (1.1). After this, as a team we decided that we would do the same 10 manual scripted tests each on the 1.1 version of the program. 

# Difficulties encountered, challenges overcome, and lessons learned

One difficulty that we came across while doing this lab was that our schedules were very different, so it was difficult at first to come up with a time to work that works for everyone. We were able to come to a compromise after looking through our schedules thoroughly. Another difficulty we encountered was our primary means of communication, discord, crashing, making use unable to communicate. We have learned our lesson, and now are able to contact each other through other ways so we don’t rely just on discord.
Since this was our first time using backlog, we had some issues getting started and using it. For instance, generating issues, editing old ones, and changing versions and things took us some time to get used  to, however we were able to overcome this and now we can use backlog efficiently. Another difficulty we encountered was that it was also our first time doing this sort of testing, and so it took us longer than expected to understand how exploratory testing worked, and how to do this testing right. We were able to overcome this issue as when we were testing, we brainstormed possible things we should check, and looked at every angle we could think about. A lesson we learned from this testing, is that it allows us to explore a lot more possible defects as it gives us the freedom to check any possible bugs we might think of. 

# Comments/feedback on the lab and lab document itself

After doing this lab, we feel much more confident about how exploratory and manual scripted testing work, and why they’re both performed on a system to debug it. We found both testing methods very useful because it can be applied to any system that we want to test. The lab did provide us very good practice for this testing and allowed us to explore both types of testing. We felt that the lab was a little difficult to follow, particularly with backlog as some of the instructions were conflicting. Furthermore, we felt that in the regression testing instructions, on the 5th step, it was a little confusing as to what was wanted of us. 
