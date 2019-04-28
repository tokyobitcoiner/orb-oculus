# orb-oculus
revisiting coding after a long, long break!

# Starting a Gridseed Orb miner with a Mac
Find out the path and device name of the Gridseed on the Mac.<br/>
Open terminal and type<br/>
ls -l /dev/cu.* <br/>
It will give you a list and you want something like this:<br/>
/dev/cu.usbmodemfa231<br/>
-S zus:/dev/xu.SLAB USBtoUART -S gridseed:all --set-device gridseed:clock=850 --scrypt<br/>
<br/>
# Pool settings
stratum+tcp://[ca.simplemulti.com:3364] = url
