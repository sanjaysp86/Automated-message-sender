# Automated-message-sender
This mehod program is used to create and generate the automate msg sender for whatapp or other social media platform

python pyautogui and installation
pyautogui is a python module helps you to automatically click and control the mouse and keyboard event. to install pyautogui you need to open your command prompt (cmd) or terminal and enter the command

1. pip install pyautogui
This code will install pyautogui in your system. If You Face any pip related issue that mean you haven’t installed python properly in your computer follow the below post to install python properly
Now you need to open WhatsApp web and log in with your WhatsApp app by scanning the Qr code shown on your desktop. After successfully logging into your WhatsApp web Now it’s time to move to the code section.
Code:
so here we are at code section where we will write the program to automate sending our WhatsApp messages.

2.import pyautogui as pg
3.import time

Here in this block of code, I have imported the pyautogui for automating typing and sending of messages and with that, I have also imported a time module to give some time interval between sending texts.

4.time.sleep(5)

I have given a 5 seconds of sleep time so that the program does not start executing the commands instantly and I have time to place the mouse cursor on the chat field

5.for i in range(100):
6.    pg.write(" i love you ")
7.    time.sleep(0.5)
8.    pg.press("Enter")

In this block of code, I have run a for loop for repeat sending of messages and used pyautogui module and write the message after that I have given a 0.5 second the time interval between each message and after that, I have given the command to press Enter button in the last line to send messages.
