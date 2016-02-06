# Emarsys
Purpose, Domains, Accountabilities defined by parent circle.

## Roles
### Lead Link - Banyo Marci
### Rep Link - Laci	
### Facilitator - Tojas
### Secretary - Marci

### Process Facilitator - Denes, Tojas
Purpose: stable velocity

Accountabilities:
- overseeing dev process and reporting to customer
- facilitating daily standups
- estimating
- reviewing all the code
- answering outer tech questions
- averting obstacles
- collecting tech info
- going to Emarsys tech demo

Domains:
- tech tools
- tech processes

### Product Owner - Banyo
Purpose:
- happy customer, happy vienna

Accountabilities:
- translating business need to user stories with acceptance criteria
- creating mockups 
- explorational testing

Domains:
- relations with EMS / PM / third parties

### Dev - Laci, Tojas, Marci, Simon, Denes
Accountabilities:
- implementing software based on user stories which meets the DoD

### Steward
Accountabilities:
- reviewing code in its domain at least weekly
- ensuring quality in its domain

#### Domains per person:
- Angular & UI: Marci
- SMPP: Marci
- Workers & RabbitMQ: Laci
- Web & API: Tojas
- Integration: Tojas
- Catch-all: Process Facilitator

## All functions & activities within the Circle

##### Policy: Dependency resolution
The assignee should resolve any emerging dependency for the current week.

##### Policy: Holidays / Home office / Sick leave notification and approval
You have to clearly distinguish between holidays, home office and sick leave. Mark it in your calendar as soon as you're aware of it.
- Holidays: Let your circles on Slack and your clients know 3x the length of your planned holiday (in workdays) before the start of it, but minimum 5 workdays before in writing
In case of Holidays and Home office, letting them know within this period doesn't mean that it's not allowed, but can be declined, if your plan is not safe to fail.
- Sick leave: notify ASAP and keep others uptodate about your how being and expected first day of work.

##### Policy: Estimation
Next week's commitment is reestimated by the team before the demo, 
taking the roadmap into account.
UI tasks' estimation must be based on existing and approved mockups.
If a UI task has backend dependencies, then the backend and frontend tasks must be defined in
separate tasks in the same user story.
If there is lack of information to estimate a user story, then estimation is
forbidden and has to be marked.

##### Policy: JIRA usage
We set the assignee and the assigner, we discuss and clarify all the AC. 
We add external dependencies as tasks for the Emarsys staff. 
If you find a bug add it to JIRA backlog.

##### Policy: Definition of well-defined
A well defined task should:
- have acceptance criteria
- contain only one UI component
- have mockups

##### Policy: Definition of done
A card only can move to done if:
- there are integration tests about the acceptance criteria
- unit test coverage is almost 100%
- deployed to stage and production
- AC is manually tested on production
- reviewed by other
- works in local
- doesn't break the build
- you informed the others about the breaking changes

##### Policy: QA
Every task must have someone who will assure its quality. 
He/She has to check on the staging environment whether all AC are met. 
Every task have to be QA-d by its assigner in JIRA with special attention to edge cases.

##### Policy: Meetings and schedule
- Governance meeting / retro: every second week on Friday (14:00)
- Standup: Daily, (9:30)
- Demo: Weekly, Thursday (15:00)

##### Policy: Demo
We don't demo incomplete features at all. 

##### Policy: Inner demo
Inner schedule for inner demo:
- Demo the features of the current sprint
- Reestimation of the commitment
- Estimation forward

##### Policy: Sick leave
If you are sick tell the team ASAP on Slack Emarsys channel. 
The rest of the team should reestimate the sprint and tell the changes to Emarsys. 
Sick people aren't counted in the reestimation for that week.

##### Policy: Timesheet
At the end of the day fill in the timesheet.

##### Policy: Standup
The default time is 9:30 AM.
It is mandatory for all the developers to attend, in case of home-office he/she should join on Hangouts.
It is not mandatory but recommended for PO-s.

The fix agenda for the meeting:
- Daily commitment (How to demo it)
- Dependencies
- Schedule next standup and tomorrow's meetings
- Timesheet
- Burndown chart
- Contribution graph

##### Policy: Home office
Let your circle know on the previous day if you're working from home all day long.
Write your request on the slack channel. If nobody has objection, you are free to stay home.

##### Policy: Feature switch
If your commit would block deployment, please use feature switches.

##### Policy: Async governance process
We use the same Async governance process as TLC. A pull request becomes eligible for async once it is posted to #emarsys on Slack.
