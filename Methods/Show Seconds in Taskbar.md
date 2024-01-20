1. press Win+R, type "regedit", and press Enter to open the Registry Editor.

2. Navigate to `Computer` > `HKEY_CURRENT_USER` > `SOFTWARE` > `Microsoft` > `Windows` > `CurrentVersion` > `Explorer` > `Advanced`.

3. In the right pane, right-click an empty space, select `New`, and then select `DWORD Value (32-bit)`.

4. name the new value `ShowSecondsInSystemClock`.

5. double-click the created value, change the value to `1` and confirm.

6. close the registry editor.

7. restart the computer for the changes to take effect.