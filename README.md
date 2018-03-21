# BootChamp for Security Hazard Junkies

BootChamp is an macOS menu bar app that makes it easy to boot into your Boot Camp Windows partition. Instead of using Startup Disk in System Preferences or holding down the Option key at startup, just select "Restart into Windows" and BootChamp will do the rest.

## Security Warning
**This software requires macOS's System Integrity Protection to be disabled. Disabling SIP makes your system more vulnerable in terms of security. If you want to use this software regardless of security problems, USE THIS SOFTWARE AT YOUR OWN RISK.**

## But why?
There are still many people using old MacPro(a.k.a. tower mac) like me. The problem is that if you install third-party GPU on a tower mac, you cannot see EFI screen when the system is booting. It means that you cannot use startup manager to select which OS to boot.
To make the problem worse, Apple's Bootcamp driver doesn't recognize APFS partition so if you want to boot to macOS again, you need to enter recovery mode and then select macOS partition as boot device.
That's why I needed a way to temporarily set what OS to boot. I found this application and added "hotkey" support so I can reboot the system into bootcamp with just a shortcut input.
But still, I don't recommend using this software since you have to disable SIP.

## Open Source Software Notice
### BootChamp
This software is a fork project of [BootChamp](https://github.com/kainjow/BootChamp) by Kevin Wojniak

Copyright (c) 2007-2015 Kevin Wojniak

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

### DDHotKey
Copyright (c) Dave DeLong <[http://www.davedelong.com](http://www.davedelong.com)>

Permission to use, copy, modify, and/or distribute this software for any purpose with or without fee is hereby granted, provided that the above copyright notice and this permission notice appear in all copies.

The software is  provided "as is", without warranty of any kind, including all implied warranties of merchantability and fitness. In no event shall the author(s) or copyright holder(s) be liable for any claim, damages, or other liability, whether in an action of contract, tort, or otherwise, arising from, out of, or in connection with the software or the use or other dealings in the software.

