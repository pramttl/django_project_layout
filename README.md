## A simple, generic django project layout

### Quickstart

        $ git clone https://github.com/pramttl/django_project_layout
        $ mv django_project_layout <my-project-name>

There you go!

### Features

* You can simply rename this repository to your project and start writing your django code.

* The layout in itself is not specific to any Django version. 
  You can use any version of django you like.

It has been created keeping in mind the following points in django development practices:

* A settings file is defined for each project.
* An app can be created in the djproject_layout directory.
* A project urls.py file is available in the top-level directory.
* Each app may have its own urls.py file
* A central templates, static directory is available.
* Each app may have its own templates, static directory.
* You add your python package dependencies to requirements.txt.


###### Tested:

The layout in itself is not specific to any Django version as mentioned before.
But just to boost your confidence; the layout has been successfully used with the following django versions:

* django 1.4.x
* django 1.5.x
