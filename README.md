# meetup_event_planning
Meta-repository for Meetup Event Task Management

## Repository Structure

### Events
All events are Milestones under Issues. 

#### New Events
When planning a new event, go to Issues (next to the Code tab above), Click on Milestones (first button to the left of "new issue"). Click the button to create a new Milestone. There are no strict format rules, just make sure it's clear what time frame the event is meant to be held in and a generally idea of what it is.

Once that milestone has been created, add any tasks that need to be done for that event under the Milestone (see "Creating a New Task").

### Creating a New Task (Issue)
Tasks are Issues, but for our use case, tasks make more sense as Issues usually refer to bugs. From the Milestones view, click on the name of the milestone. From the Milestone's page any new issue created will automatically be linked to that Milestone. You can also link to the Milestone when creating a new issue through the "Milestone" section on the Right of the new issue creation page.

Ideally all tasks should be tied to a Milestone.

In the description of the task, clearly outline what needs to be done in order for the task to be closed out or considered "done". For example, Meetup Events need a place to happen so one task is to reserve meeting space. The Subject can be simple, "Reserve Meeting Space" and the description should contain sufficient information for anyone that is not you to be able to pick up the task and know what needs to be done. So you might say "Reserve a space in the downtown waterfront area, preferably an OHSU classroom." Github allows you to embed a checklist and I recommend using it if it makes sense for your task. So items for this might include "- contact @github_user to reserve an OHSU classroom on Jan 29.", "- identify alternative meeting spaces if OHSU is not available", "- update Meetup Event description with location information", "- take photos and provide a map for the Meetup Event description".


### Picking up Tasks
If you start work on a task, assign it to yourself and tag the issue as "In Progress" so it's very visibly clear that you're working on it. I recommend that you leave a comment indicating what you are going to do and what will be your next endpoint. For example, if the task is "Reserve Meeting Space", then you might leave a comment along the lines of "Emailed @github_user to reserve an OHSU Classroom on the waterfront for Jan 29." 

When updating based on talking to other people, if you don't know the person's github username then you don't need to use it, name works too. The advantage of mentioning the Github username is they will get pinged and can even respond on the issue directly. Either way, it's good to call out who you are contacting in order to get something done!

Note that multiple people can be assigned to one task. In the above example for "Reserve Meeting Space", someone else might pick up the item "- identify alternative meeting spaces if OHSU is not available". They would add themselves and leave a comment "My apartment complex is on the waterfront and has a reservable community room. I will follow up with them to check availability and any costs for Jan 29".

## Updating Tasks
Make sure you update the task as you make progress on it! So per previous example, if you get a response, then update the issue "Heard back from @github_user, they are looking into it and will get back to me by Jan 5." Or, if it's been a week and you haven't heard back, you might say "Haven't heard back from @github_user, sending followup email and also pinging our mailing list to see if anyone else from OHSU can assist."

If you've gathered additional information as part of the task, it might be worth updating the original issue description, espeically if the information you've gathered results in additional work items! Using the example of meeting space above, let's say someone else picked up "research alternative meeting spaces". They might add a new section once they've gotten the information, "Alternative Meeting Locations: Community Room at @missaugustina's apartment complex: $25, available Jan 29, visitors buzzed in by Augustina and take elevator to 2nd floor, we should make signs".

Additionally they could leave a comment "spoke with apartment complex management regarding community room. Updated original issue description above." It's a bit redundant and not a big deal if not done but sometimes over-communication is better when collaborating with a group.

