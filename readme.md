The Display definition file needs to go in the path: /System/Library/Displays/Contents/Resources/Overrides

You need to boot the machine holding cmd+r to be in recovery mode, open Terminal and type "csrutil disable" to disable system integrity checker. After copying the file enter "csrutil enable" and then restart the machine normally. 
