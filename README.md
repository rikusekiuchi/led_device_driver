# led_device_driver

Device driver that can handle LED on Raspberry Pi.

#Operation check

$ make
$ sudo insmod myled.ko  
$ sudo chmod 666 /dev/myled0  
$ echo 1 > /dev/myled0 //flash  
$ echo 0 > /dev/myled0 //solid  
$ sudo rm /dev/myled0  
$ sudo rmmod myled  
