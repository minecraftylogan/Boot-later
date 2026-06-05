<img width="206" height="184" alt="image" src="https://github.com/user-attachments/assets/52e475bd-53e6-4aa5-b5bb-1b9767f5120c" />


# Boot-later
Useless macOS hang that allows you to boot .app's/Installers later in bootpicker on M1+
## Instructions
* Download Main
* extract .app from dmg and place .app in dmg's place
* Unzip Main and point terminal at Main and use command "dd if=/dev/zero bs=1M count=1000 >> .VolumeIcon"
* Use shift+>+cmd to show hidden files in Main
* Drag and drop everything on to a external USB drive / SSD formatted as APFS. (Note, .VolumeIcon may take awhile to transfer)
## How to Use
* Shut-down Mac and hold powerbutton to open bootpicker
* Highlight the device you want to boot from (Besides Boot-later USB)
* Plug in Boot-later USB, wait until you see a magical rainbow lollipop.
* Press enter on the device you want to boot from (should not do anything)
* Once Bootpicker loads (a minute about), your selection should load, or just unplug the Boot-later USB
* Congratz
## Creditz
* Asahi Linux Team for letting me steal their .VolumeIcon
* Apple for macOS
* MacAdmin Team for being awesome. <3
## Notes
* Finish Install.app is a placeholder for bootpicker to see the USB drive, it will just error out if you try to open it. 
## To-Do
* Find the equation of (boot-picker * padding amount) = amount of time spent hanging. 
* No AI used. 
