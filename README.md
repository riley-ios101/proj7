# Project 7 - *Task List*

Submitted by: **Riley Dou**

**Task List** is an app that allows you to organize your tasks. You can create new tasks, edit existing tasks, and mark tasks as complete to see your progress! You can also view each task in a calendar, so you can easily see which tasks are set for which date.

Time spent: **3** hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] App displays a list of tasks
- [x] Users can add tasks to the list
- [x] Session persists when application is closed and relaunched (tasks don't get deleted when closing app) 
  - [x] Note: You have to quit the app, not minimize it, in order to see the persistence.
- [x] Tasks can be deleted
- [x] Users have a calendar view via navigation controller that displays tasks    


The following **additional** features are implemented:

- [x] Tasks can be toggled completed
- [x] User can edit tasks by tapping on the task in the feed view
- [ ] Be able to view detais of the task in the calendar view
- [ ] For tasks that have a location, add a map view

## Video Walkthrough

[Demo Pt.1](https://imgur.com/52XH0aj)
[Demo Pt.2](https://imgur.com/DTilFWz)

## Notes

A challenge was implementing the edit task functionality. When clicking on a task to edit, it returned a new uuid instead of the uuid of the existing task; thus, duplicates of the task were added instead of replacing that task.

## License

    Copyright [2024] [Riley Dou]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
