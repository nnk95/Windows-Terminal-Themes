# Windows Terminal: Themes
Themes for Windows Terminal

`settings.json` file is when you click on the down arrow then settings.

# PowerShell: 7
Settings for PowerShell: 7
-----

While in PowerShell 7, within Terminal: `notepad $PROFILE`. This should bring up a file (create new if necessary). Within this file, input:

```
Import-Module posh-git
Import-Module oh-my-posh
Import-Module Terminal-Icons
Set-PoshPrompt -Theme slim
Clear
```

Save the file, return to PowerShell: 7 within Terminal and input:
```
. $PROFILE
```

# PowerShell: 5
Settings for PowerShell: 5
-----

While in PowerShell 5, within Terminal: `notepad $PROFILE`. This should bring up a file (create new if necessary). Within this file, input:

```
Import-Module posh-git
Import-Module oh-my-posh
Import-Module Terminal-Icons
Set-Theme Operator
Clear
```

Save the file, return to PowerShell: 7 within Terminal and input:
```
. $PROFILE
```
