# km3

Dear comrade XVortex successfully ported firmware 0.3.7 from Ugoos for some boxes on S905X2 and S905X3 processors. For Mecool KM3 /KM9 with LPDDR4 RAM, the XVortex 0.3.7 port from Vosen V1 was perfect. Port 0.3.7 is currently compatible with all KM3 and KM9 set-top boxes with KM9 X2 LP4 V2.X board versions. In addition, the firmware is suitable for some instances with KM9 X2 LPDDR4X V3.0, KM9 X2 LPDDR4X V3.1 and KM3 X2 LPDDR4X boards, in which the manufacturer installed SpecTek LPDDR4 memory instead of LPDDR4x from Hynix (marked with the letter S in a white diamond).
It should also be borne in mind that on the KM9 Pro set-top box with the KM9 X2 LP4 V2.2, KM9 X2 LP4 V2.1 board or any other board, but with the IT-Link IT6335 module, you will get a broken WiFi, but Bluetooth will work. Unfortunately, no solution has yet been found for this problem.
The only change made to the original port of revision r3 for Vosen V1 is changing the model name of the set-top box to KM3 .

All the main functions of the set-top box and chips from Ugoos have been tested on Mecool KM3 Collective version KM9 X2 LP4 V2.2.
There is one easily eliminated nuance and a couple of unremovable ones that you can live with:

To ensure that the set-top box is turned on by the stock remote control via IR, before pairing the remote control via Bluetooth, scan and save the code of the On / Off button in the menu Device settings - Power - Additional IR power button - Start scanning. When scanning, long press the button (until the shutdown menu appears), then press Back, make sure the button is scanned and save the code. The On/Off button of the stock remote has the code a659ff00.
After saving the button code, you can proceed to pair the remote in the Remotes and accessories menu.
Attention! Adding the IR code for the On/Off button of the remote control should be done first!

Unremovable nuances and features:
In this firmware, it was not possible to implement the operation of the LED indicator according to the Mecool proprietary color scheme . The indicator displays the following states:
- blue glow - the set-top box is on or sleeping;
- red glow - the prefix is ​​​​off;
- no glow - the set-top box is in hibernation (if this mode is selected for the shutdown button) or if there has been a power outage. The device will remain in the off state after connecting the power supply and can be turned on with the remote control, CEC or the Recovery (Reset) button. This proprietary feature from Ugoos works when the Disable auto-on option is enabled in the Power menu.
The stock remote does not control the set-top box in the downloaded Recovery. To work in Recovery you will need a USB device (remote control, mouse or keyboard).
