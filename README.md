# Basic Network Scanner

In this project, I will be creating a basic network scanner via the ping3 and ipaddress module. Throughout this project, I will be adding new modules in to create a complex network scanner.

# Overview

A network scanner is a tool used for analyzing hosts that are available on the network. It allows the user to map the network to find devices that are connected to the same network. One of the most basic function of network scanner include an ICMP echo request and ARP request.

## ICMP

Internet Control Message Protocol (ICMP) is a protocol to send error messages and operational messages between networks devices,  determining network communication issues. It can be use for two purposes: Error Reporting and performing network diagnostic. It is a network layer protocol.
ICMP can be used to determine if data is reaching target. We will be using ICMP echo request, also known as ping. The ICMP echo-request and echo-reply messages are commonly used for the purpose of performing a ping. Ping determine if devices is reachable on the network by sending a request to it.This is like "knocking" on every door in a neighborhood to see which ones respond. In this case, you're checking which devices (like computers, printers, etc.) on a network are active.

## Libraries

**ping3** is a is a third-party library that can be easily installed. Once installed, you can import the ping function from the ping3 module and use it to send ping requests. <br> **ipaddress** is included in the Python standard library and provides a set of classes and functions for working with IP addresses and networks. It provides a simple way to generate a list of IP addresses within a given range using the ip_network() function.



