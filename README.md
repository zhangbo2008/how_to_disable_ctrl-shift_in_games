# how_to_disable_ctrl-shift_in_games


```
GroupAdd, game , ahk_exe SC2_x64.exe      ;注意这种语句要放最前面才起作用
GroupAdd, game , Warcraft      ;注意这种语句要放最前面才起作用
GroupAdd, game , Dota 2      ;注意这种语句要放最前面才起作用
GroupAdd, game , ahk_exe ComeOn.exe      ;注意这种语句要放最前面才起作用=================我们禁止游戏里面的ctrl+shift切输入法.
;GroupAdd, game , SC2_x64      ;注意这种语句要放最前面才起作用
GroupAdd, game , ahk_exe notepad++.exe 

GroupAdd, game , daojian.exe      ;注

SetTitleMatchMode, 2

SetTitleMatchMode, slow


#IfWinActive  ahk_group game

^LShift::
```
autohotkey
