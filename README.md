# DellE5540OpenCoreBigSur
My OpenCore EFI working on a Dell E5540.

I've been trying to get Big Sur on my Dell E5540 but doing everything manually keeps failing time after time. Following the install guide at https://dortania.github.io/OpenCore-Install-Guide/ There was something I couldn't get working.

I found Axemere's E5440 repo at https://github.com/axemre/OpenCore-Dell-Latitude-E5440 and this worked out of the box with a few issues like going to sleep at every reboot. I updated OpenCore to the current release, and swapped all kexts and drivers with updated versions where available.

Using Emere's SSDTs and Plist.conf with Serial, ROM and UUIDs generated with GenSMBIOS as guided on https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html#using-gensmbios I can use everything on the laptop except the trackpad. Sleep, Sound, WiFi and Bluetooth all work, and while Fn keys aren't quite there, volume buttons work and Brightness control slider does adjust the screen.
