# TODO list API



## Introduction

TODO list API lets you search, fetch, create to-do-items and also group them together. One has to use RESTful calling style to access and edit TODO list API.


| Method       	 | HTTP Request  	| Description|
| ------------- |:-------------:	| -----:      |
| getGroups     | GET  /group           | Returns all the user's task lists.|
| getSpecificGroup| GET /group/:groupId | Returns the user's specified task list |
| deleteGroup   | DELETE /group/:groupId| Deletes the entire user's specified task list. |
| addNewGroup   | POST  /creategroup    | Creates task list for to-do-items e.g."Shopping List"|
|getGroupItems  | GET  /grouptasks/:groupId | Returns all the to-do-items from a specific list/group.|
| getAllTasks   | GET  /tasks           | Returns all the to-do-tasks from all lists/groups.|
| getSpecificTask| GET  /task/:taskId  | Returns specific task.|
| addNewTask   | POST  /create         | Creates a new to-do-task inside a specific list/group. /nNote: Provide group id in request's header; e.g id:123|
| deleteTask    | DELETE  /remove/:groupId/:taskId| Deletes the user's specified to-do-item.|

## Authors

* **Sher Sanginov**
