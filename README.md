# Project 6

Program represents PyQt5 implementation for the Curling League Manager.

# Installation

To install the program use the setup.py script with installation path in the first argument.

  python setup.py <installation_path>

# Interface

Interface is multi-window including the following windows: main window, league editor and team editor.

## Main window

Main window shows list of leagues in the current database. Has load/save menu items to select the file to load/save.
Has buttons to:
o	Delete a league
o	Add a league (the league name can be input directly in this window)
o	Edit a league

## League editor

League editor shows list of teams in the league being edited. Has import/export menu items to select files for import/exports.  
Has buttons to:
o	Delete a team
o	Add a team (the team name can be input directly in this window)
o	Edit a team

## Team editor

Team editor shows list of team members in the team being edited.
Has buttons to
o	Delete a member
o	Add a member (the member's name and email can be input directly in this window)
o	Update a member (the member's name and email can be input directly in this window)
