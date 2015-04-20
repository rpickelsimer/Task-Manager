Ryan Pickelsimer
Adv Mobile App Dev

***** April 20, 2015

Used SharedPreferences to pass data between Actvities. Also fixed column issues in TableLayout.


***** April 19, 2015

Used startActivityforResult() to handle passing data. This eliminated the need for IntentHelper.java.
Also eliminated Date and Time classes and folded into Task.
Fixed issues with cancel button.


***** April 12, 2015

This program meets the requirements set forth in the week 1 module programming assignment. 
The application has one screen that list tasks and info while another is used to add a task with date time and task type.

Main program source code (Because of the small size of the project, everything is included in the package:
edu.rasm.pickel.taskmanager):

Manifest:
	AndroidManifest.xml

Activities:
	TaskListActivity.java	-->	application entry point
	AddTaskActivity.java

Layouts:
	activity_task_list.xml
	activity_add_task.xml
	picker_frag.xml

Java classes:
	IntentHelper.java
	Task.java
	Date.java
	Time.java

resources:
	strings.xml