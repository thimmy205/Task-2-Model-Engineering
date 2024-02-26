# Task-2-Model-Engineering

1.2 Task 2: Automation of Standby Duty Planning for Rescue Drivers via a Forecasting Model
Case description:
As a data science consultant, you are invited to work on a project within Berlin’s red-cross rescue service. The HR
planning struggles with the current standby-duty plan. They ask for your expertise on predictive models in order
to improve the current planning logic.
Every day a certain number of rescue drivers are on duty. However, due to short-term sickness of rescue drivers
or an unusual amount of emergency calls often more drivers are needed than initially expected. Hence, a certain
number of standby-drivers are kept “on hold” and activated when needed. Therefore, in the current approach 90
rescue drivers are daily kept on standby.
As colleagues from the planning claim, there are seasonal patterns - for instance, during winter months more
rescue drivers call sick – which are not incorporated into the current approach. Moreover, sometimes there are
not enough rescue drivers even when all 90 standby-drivers are activated so that drivers are called for work even
on their days off.
It is important to know, that the duty plan must be finished on the 15th of the current month for the upcoming
month. This means, for instance, that the duty plan for November must be finished on the 15th of October.
Project Aim:
Help the HR department with planning to estimate the amount of daily standby rescue drivers via a prediction
model more efficiently. Here, efficient means that the percentage of standbys being activated is higher than in the
current approach of keeping 90 drivers on hold. It also means that situations with not enough standbys should
occur less often than in the current approach. Note that the plan must be finished on the 15th of the current month
for the upcoming month.
Data Set:
The data set and all relevant information from the business side (sickness dataset, number of emergency calls per
day) are given in a separate *.zip folder, which is available in myCampus, under the section Case Study.
Task Description:
The task consists of both coding and conceptual steps. Here is a list of tasks, which should be included in your
final document:
● Structure the project via the CRISP-DM or Team DS methodologies and give a recommendation of how a git
repository for the project could look like. Note that you do not have to structure your final code according to
your git-repository proposal.
● Assess the quality of the provided data set. Prepare and visualize your findings of the initial data analysis
in order that business stakeholders can understand them in a clear and easy way.
● Provide a baseline model as well as an accurate predictive model, which fulfils business requirements,
i.e. the amount of activated standby-drivers is maximized, but having not enough standbys is minimized.
● In order that the business places confidence in your model, discuss the importance of the individual features
and make the results of the model interpretable. Moreover, a sophisticated error analysis is very important
for the business to understand the cases in which your approach could potentially fail.
● In the last step of the project, give a proposal of how your model could be used by the business in everyday
work, for instance, via a graphical user interface (GUI).
● Finally, do not forget to attach the code to the final submission document. 
