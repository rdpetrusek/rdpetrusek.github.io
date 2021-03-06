---
layout: post
title: What's in a user story?
---

A user story will likely go through many iterations.

<img src="https://raw.githubusercontent.com/rdpetrusek/rdpetrusek.github.io/master/images/metamorphosis.jpg" height="200px"/>

 It starts out in the product backlog with minimal information. During backlog grooming, more information may be added. Eventually the user story may find itself at the top of the priority list and pulled in to a sprint. During this transition, more information will be added.

## User Story In The Product Backlog

### **How do I write a user story?**

There are different styles of writing user stories. One of the most common is the [*As a _ I want _ so that _*](https://www.mountaingoatsoftware.com/blog/advantages-of-the-as-a-user-i-want-user-story-template) template. This allows the reader to understand who wants the value, what the change is, and what value it provides.

### **Who can put a story in the product backlog?**

Some product owners allow anyone to put stories in the product backlog, but this can create a product backlog filled with duplicate stories. Some product owners may only allow certain individuals to put stories in the backlog to avoid this issue.

*It's a good practice to first search the backlog and make sure the story you're putting in the backlog doesn't already exist.*

<img src="https://github.com/rdpetrusek/rdpetrusek.github.io/blob/master/images/spidermans.jpg?raw=true" width="400px"/>

The product owner is responsible for the [product backlog](https://www.scrum.org/resources/what-is-a-product-backlog), so work with the product owner and find out what they prefer.

### **How much information does a user story need to go into the product backlog?**
 
Just enough information to remember to have a conversation.

<img src="https://raw.githubusercontent.com/rdpetrusek/rdpetrusek.github.io/master/images/reminder.jpg" width="350px"/>

---

## Backlog Grooming


### **What is backlog grooming?**

[A timeboxed meeting where user stories in the product backlog are analyzed to try and get acceptance criteria, additional information necessary to complete the user story and meet the definition of done, and possibly a rough estimate.](https://www.agilealliance.org/glossary/backlog-grooming/)

It's possible to estimate a story without acceptance criteria during backlog grooming. The estimate is more likely to be inaccurate, but it does give a rough idea of what to expect in terms of effort.

<img src="https://raw.githubusercontent.com/rdpetrusek/rdpetrusek.github.io/master/images/rough-estimate.jpg">

### **Who attends backlog grooming?**

The product owner and some or all of the development team

---

## User Story In The Sprint Backlog

[Sprint planning](https://www.scrum.org/resources/what-is-sprint-planning) or kickoff is the scrum ceremony where the scrum team decides what user stories to bring in to the sprint backlog to work on in the upcoming sprint.

### **What does a user story need to have before it can be brought into a sprint?**

A user story should have **acceptance criteria** and an **estimate** of effort. 

Without acceptance criteria, a user story will more than likely not be properly estimated. Finalizing acceptance criteria during sprint planning gives all members of the team the opportunity to understand the goal of the user story and hopefully provide better estimates.

In addition, a user story should be able to be completed within one sprint. 

### **What do you mean by acceptance criteria?**

Acceptance criteria are conditions that must be met for a story to be accepted by the consumer of that work. Acceptance criteria defines **what** not **how**.

**What**: The user should be able to search for images

**How**: The user should enter the name of the image into a textbox, then click on a button that says "Search". After the button is clicked the images should appear in alphabetical order by image name.

<img src="https://github.com/rdpetrusek/rdpetrusek.github.io/blob/master/images/many-requirements.png?raw=true" />

### **Why can't a user story be estimated accurately without acceptance criteria?**

Let's say I have a user story that reads "Drive to work". I might think, "that will take between 30 and 90 minutes, depending on traffic" and based on other user stories that works out to be 5 points of effort. 

<img src="https://raw.githubusercontent.com/rdpetrusek/rdpetrusek.github.io/master/images/theres-more.png" height="300px"/>

One day I start driving to work and when I'm half-way there the user story changes to "Drive to work, and bring a pen with you". 

I might have a pen in the car that's easy to grab, so that doesn't change my estimate. Or I may have to stop at the store to buy a pen, and the store may be far off of my normal route to work which might double my original estimate.

### **What happens if the highest priority user story in the product backlog can't be completed within one sprint?**

If this occurs, it's important to break down the user story into smaller user stories that each provide value. 

<img src="https://raw.githubusercontent.com/rdpetrusek/rdpetrusek.github.io/master/images/smallergoals.png" width="250px"/>

A user story must be able to be completed within one sprint. The process of breaking down user stories might also involve [**epics** and **themes**](https://www.mountaingoatsoftware.com/blog/stories-epics-and-themes) 

### **How do we estimate a user story?**

Estimation can happen in a number of ways. Two common methods are **points** and **[t-shirt sizes](https://www.mountaingoatsoftware.com/blog/estimating-with-tee-shirt-sizes)**. Points are typically part of the [fibonacci](https://en.wikipedia.org/wiki/Fibonacci_number) sequence. 

Some teams require user stories be below an estimate threshold. The larger a story's effort is, the less accurate that estimate tends to be.

<img src="https://raw.githubusercontent.com/rdpetrusek/rdpetrusek.github.io/master/images/hand_holding_eiffel_tower.jpg" height="400px"/>

### **If we decide to pull a user story into the sprint, do we have to go by the estimate on the story?**

Every story that is brought in to the sprint should be estimated during sprint planning. If the development team decides to estimate the story and it happens to be the same as the current estimate, then the estimate stays the same. The development team may decide to change the estimate.

### **What happens if the acceptance criteria changes in a user story that is in the sprint backlog?**

The acceptance criteria *shouldn't* change for a user story in the sprint backlog. 

<img src="https://raw.githubusercontent.com/rdpetrusek/rdpetrusek.github.io/master/images/bad-idea.gif">

If this happens, the estimate may no longer be valid and the sprint could be endangered. 

If new value is identified that should exist in addition to the user story in the sprint backlog, then a new story should be created and put into the product backlog.

If the user story doesn't provide enough value, or any value at all, then it should be removed from the sprint. 

If the product owner creates a new user story in the product backlog, the team may decide to pull it into the sprint.

### **If I don't know how hard a task is going to be, how can I estimate it?**

<img src="https://raw.githubusercontent.com/rdpetrusek/rdpetrusek.github.io/master/images/way-to-everest.jpg" width="400px"/>

An estimate should consider uncertainty, and make a reasonable accomodation for the unknown. But remember, it is an **estimate** not an **actual**. Until we do the work, we can't know the actual time it will take.


## Why are there so many rules?

Many of these ideas are recommendations. Scrum provides a framework for teams, and if something doesn't work for your team (and isn't part of the scrum framework) then feel free to stop doing it. No two teams will be the same, and so it would not work for two teams to have the exact same process.
