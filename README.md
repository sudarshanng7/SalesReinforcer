# SalesReinforcer
#### Background:
A technology company in the Education industry offers various services to customers ranging from startups, SMEs and enterprises to help them upskill. The company wants to develop a platform that the customers can use to benefit from the opportunities and services offered by the company. In line with this goal, the sales team is looking for ways to first understand the underlying patterns in their CRM data, second optimize the user acquisition pipeline to improve their company’s sales funnel with the ultimate goal to create the best user experience.

#### Data Description

The dataset from the company is anonymized to exclude identifying customer information, such as names, emails, etc. Each row in the dataset represents a potential customer. Attributes starting from “Id” to “Interested In” consist of each person’s demographic information, such as where they live, or what training they have. Starting with “Message State” to “Subscribed” indicates the steps or attributes for the user acquisition pipeline and illustrates the different steps of customers lifecycle, starting with the initial contact to a prospect to qualified leads, to finally subscribing and becoming a customer.

The dataset contains the following features
* `ID` Candidate ID, always Filled (Numeric)
* `Country` Candidate's demographic information, contains blanks
* `Education` Candidate's education level encoded from B1 to B30, contains blanks
* `First Contact` Date of First Contact, contains blanks
* `Last Contact` Date of Last Contact, contains blanks
* `Status` Categories of 1st message, 2nd message, 3rd message or blank
* `Stage` Categories of subscribed already, declined/canceled call, did not join the call, interested, not interested, do not contact or blank
* `First Call` Date of First Call, contains blanks
* `Signed up for a Demo` Date of When they signed up for Demo, contains blanks
* `Filled in Customer Survey` Date they filled customer Survey, contains blanks
* `Did Sign up to the Platform` Date Signed up to platform, contains blanks
* `Account Manager Assigned` Date Account Manager assigned, contains blanks
* `Subscribed` Date Subscribed, contains blanks


#### Goals:

The main goal of this project is to design and develop a Reinforcement Learning agent to optimize the user acquisition pipeline that would help us discover the optimal attributes/steps/actions to increase overall sales.

