Persian Calendar
================

A Persian (Jalali/Farsi) calendar which provides a basic appindicator.


Screenshot
================
![screenshot](data/Screenshot.png)


Requirements
================

python-appindicator

Khayyam python package (http://pythonhosted.org/Khayyam/)


Installation
================

Note: Arch Linux users can install it from AUR (https://aur.archlinux.org/packages/persian-calendar/)

First make sure *Khayyam* and *python-appindicator* is installed:

    sudo apt-get install python-pip python-appindicator
    sudo pip install Khayyam

Download Persian calendar (make sure all steps run successfully):

    cd ~
    wget -O persian-calendar.tar.gz https://github.com/183amir/persian-calendar/tarball/master
    mkdir persian-calendar
    tar -xf persian-calendar.tar.gz -C persian-calendar --strip-components 1
    cd persian-calendar
    chmod +x persian-calendar.py

Now press Alt+F2 and run the program from there by pasting the below command:

    ~/persian-calendar/persian-calendar.py


Run at startup
================

To make the program run when you login:

In Ubuntu, run *Startup Applications* and press add

Name:

    persian-calendar

Command (you should replace USERNAME with your username:

    /usr/bin/python /home/USERNAME/persian-calendar/persian-calendar.py

Comment:

    Persian Calendar Indicator


Support or Contact
================

Having troubles? Fill an issue at *https://github.com/183amir/persian-calendar*
or Contact me at *183.amir@gmail.com*.
