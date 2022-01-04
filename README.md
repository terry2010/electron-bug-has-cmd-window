# electron-bug-has-cmd-window
report a electron bug

platform:windows 7/windows 10

after pack the soft, electron run execSync/spawnSync/elecFileSync always show a black cmd windows.

------

step:

1.  npm run test 
     
    1.1  press ctrl-A  ctrl-B ctrl-C to see Expected Behavior
    
2. npm run pack
   
    2.1  open dist\trybug-win32-ia32\trybug.exe
    2.2  press ctrl-A  ctrl-B ctrl-C to see Actual Behavior , it always show a black cmd window