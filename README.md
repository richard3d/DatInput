DatInput
========

**A free, lightweight and minimally invasive input manager for Unity3D**

Contact: [richard3d@gmail.com][1] via email or [@RichardCBecker][2] via Twitter

FEATURES
--------

- Uses Unity's native Input API (no code changes)
- Editor Window for assigning controls (zero setup code required)
- Multiple controller support
- Default multiplatform keybinding (Mac/Win) for common controllers (Xbox 360, PS3, etc)
- Mouse and keyboard control definitions automatically assigned to first player


HOW TO USE DATINPUT
--------------------

- Copy ```DatInputManager.cs``` to a subfolder named 'editor' in your project's 'assets' folder
- Open ```DatInputManager.cs``` in the Unity Editor via 'Window->DatInput Manager'
- Choose default control type and the max number of players/controllers you wish to support
- Fill out control settings (you must click save for the settings to take effect)
- You can see your changes reflected in the standard Unity Input Manager every time you save
- Use the standard Unity Input API to access input, prefixing action names with "Joy#" e.g. ```Input.GetAxis("Joy0 Move")``` - get movement from player 1, ```Input.GetButton("Joy2 Attack")``` - see if player 2 pressed attack

NOTES
-----

- Any mouse or keyboard controls will only be assigned to player 1.
- Currently DatInput does not feature control remapping during runtime as this would require
writing a completely separate Input library; however, it will be available in the coming months.

THANKS TO
---------

- Alec Holowka for sharing InputX which helped inspire DatInput
- PL Young for the excellent tutorial which provided technical expertise for DatInput


[1]: mailto:richard3d@gmail.com
[2]: https://twitter.com/RichardCBecker

[98]: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
[99]: http://tmpvar.com/markdown.html
