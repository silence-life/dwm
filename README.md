![dwm-6.4-overview-layout](https://github.com/silence-life/dwm/blob/main/dwm-grid.png)  
      +patch dwm-awesomebar-20230431-6.4.diff  
      +modified config.h  
      +patch dwm-hide_vacant_tags-6.3.diff  
      +patch shiftviewSkipVacant and modifed config.h  
      +newempty,means open the first vacant tag.(other vacant tag is invisible)  
      +patch dwm-pertag-20200914-61bb8b2.diff  
      +patch runautostart  
      +if (nmaster>2) nmaster=1;  
      +pressing super+0 again will return the tag which own the selected window  
      +overview layout  
      +to open the specified tag will execute the specified command  
      +patch dwm-scratchpad-20200727-bb2e7222baeec7776930354d0e9f210cc2aaad5f.diff and +pop(c)  
      +patch dwm-uselessgap-20211119-58414bee958f2.diff  
      +scratchpad super+u KEY do both hide and remove hide  
      +bemenu  
      on tile layout,when click the unselected taskbar,the window pop as main window  
      when togglefloating,the window go to the center of the screen  
      fix overview layout bug and make it more valid  
      modify config.h  
      +patch dwm-systray-6.4.diff  