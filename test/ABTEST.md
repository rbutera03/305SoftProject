# Walk Point URI - A/B Testing Ideas

## Test Idea #1
A/B Test Name: Screen(s) Background Color

User Story Number: US1

Metrics: User Satisfaction, Retention Rate

Hypothesis: We aim to improve user retention and satisfaction by testing different background colors vs background images on the login screen. My hypothesis is that users who see a more vibrant background color or image will have a higher user satisfaction score and a greater likelihood of returning to the app compared to those who see a more neutral background or solid color.

Experiment:

Audiences: 50% of users will see Variation A (Vibrant Background), and 50% will see Variation B (Neutral Background).
Duration: 2 weeks
Randomization: Users will be randomly assigned to either variation using Firebase Remote Config.
Tracking: Set up Firebase Analytics to monitor the response rates and user engagement for each variation. Key events to track include login success rate, time spent on the login screen, and app usage following login.

Variations:
Variation A: Background color is a background image (e.g., URI Campus).
Variation B: Background color is a solid color (e.g., light gray).

## Test Idea #2
A/B Test Name: Login Landing Page: Routes Page vs. Map Page

User Story Number: US2

Metrics: User Engagement, Retention Rate, Task Completion

Hypothesis: We aim to increase user engagement and retention by testing which landing page following login leads to a smoother user experience. My hypothesis is that users who land directly on the Routes Page will feel more guided and engaged with the app compared to those who start on the Map Page. This could lead to higher retention and task completion rates.

Experiment:

Audiences:
50% of users will see Variation A (Routes Page).
50% will see Variation B (Map Page) as the initial landing page post-login.
Duration: 2 weeks
Randomization: Users will be randomly assigned to either variation using Firebase Remote Config
Tracking: Set up Firebase Analytics to monitor engagement, navigation flow, and time spent on the initial landing page. Key events to track include navigation from login, route/task initiation, and time spent on each page.

Variation A: Users land on the Routes Page upon login.
Variation B: Users land on the Map Page upon login.

## Test Idea #3
A/B Test Name: Route Naming: "Create Route" vs. "New Route"

User Story Number: US3

Metrics: User Engagement, Task Completion Rate, Bounce Rate

Hypothesis:
We aim to improve user clarity and task completion by testing the naming of a key route. My hypothesis is that users who see "Create Route" will understand the action better and complete tasks more effectively than those who see "New Route," leading to higher engagement and lower bounce rates.

Experiment:

Audiences:
50% of users will see Variation A ("Create Route").
50% of users will see Variation B ("New Route").
Duration: 2 weeks
Randomization: Users will be randomly assigned to either variation using Firebase Remote Config.
Tracking: Set up Firebase Analytics to monitor engagement and task completion rates for each variation. Key events to track include clicks on the route option, task completion within the route, and navigation bounce rate.
Variations:

Variation A: The route is labeled as "Create Route."
Variation B: The route is labeled as "New Route."

## Test Idea #4
A/B Test Name: App Rating: Use Again or Recommend to Others

User Story Number: US4

Metrics: NPS, User Satisfaction, Retention Rate

Hypothesis: We aim to improve user retention and referral rates. By determining which question (use again or recommend) generates more positive feedback, we can optimize our user feedback process. My hypothesis is that users who are asked if they would use the app again are more likely to give a positive rating compared to users who are asked if they would recommend the app to others. 

Experiment:
  Audiences: 50% of users will see Variation A (Use Again), and 50% will see Variation B (Recommend to Others).
  Duration: 2 weeks
  Randomization: Users will be randomly assigned to either variation using Firebase Remote Config.
  Tracking: Set up Firebase Analytics to track the response rates and user engagement for each variation. Key events to track include feedback submission and subsequent app usage.

Variations: 
  Have a page with a survey for users asking them a question and way to rate it 1-10 (slider or dropdown menu), only change the question phrasing on the page.
    Variation A: Question: "Would you use this app again?"
    Variation B: Question: "Would you recommend this app to others?"
