# Ultra-Low-Profile-USB-Header

A USB header for PC motherboards designed to be as minimal as possible. It may interfere with components on some motherboards. Its intended use is for keeping small flash-drives, wireless controllers, or USB license keys inside a computer enclosure. 

It can also be a powerful tool for computer techs who can keep two USB tools together such as a diagnostics OS on flash drive alongside a wireless keyboard/mouse receiver.

My personal use case is in a custom built super slim NAS enclosure that runs UnRAID. My OS is on a tiny flash drive and the second slot holds a 2.4ghz receiver for a thumb keyboard/trackpad thing. All current offerings I could find were too tall for my needs or were a wired assembly, this is much cleaner.

# Build of Materials

- Vertically Aligned Double USB-A Socket (Shortest Possible) - Avalable on AliExpress
- 2x5 Socket Header 2.54mm Spacing - Avalable on AliExpress
- VDBX.io ULPUH PCB - https://easyeda.com/clomads/usb-header-for-motherboard
- Black Silicone (Optional) - Available on Amazon or your local hardware store

TODO: Links

# Assembly

You will need to shorten the leads on the 2x5 Socket Header so the USB Socket will fit flush on the other side. This can be done with snips, but I find it best to sand the pins down with a disc sander and low grit sandpaper (60/80). You will likely mess up a few at first with either method but the goal is to get the pins to be slightly shorter than the board is thick.

Solder the header on making sure its solder joints are secure and as flush as possible on the top.

Solder the USB-A Socket on and clean up its connections. Use snips if necessary.

Fill the alignment pin socket with silicone and let it cure.

Use it - PLug it into the USB 2.0 header on any* motherboard.



* I have not tested this on every motherboard but I assume it should fit most. On mine, it blocks a portion of the F_Audio header which may prove difficult if I choose to use it, though there is plenty of clearance to prevent a short.

TODO: Embed photo of it on my motherboard.


Licensed CC-BY-SA 4.0

