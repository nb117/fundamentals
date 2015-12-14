#!/usr/bin/env python3

"""The Ever So Freaking Glorious Hello World Program"""

import skilstak.colors as c
import time

def print_multi(message)
    while True:
        print(c.clear + c.multi(message))
        time.sleep(0.5)

def print_plain(message):
    print(c.cl + c.x + message)

def print_foreva(message):
    while True:
        print(c.cl + c.x + message, end=" ")

def print_color(messege):
    print(c.cl, end="")
    while True:
        print(c.rc() + message + c.x, end=" ")

def parse_args():
    from sys import argv

    name = "World"
    option = ""

    if len(argv) > 2:
        option = argv[1]
        name = argv[2]
    elif len(argv) == 2:
        if argv[1].startswith("-"):
            option = argv[1]
        else:
            name = argv[1]
    return name, option
