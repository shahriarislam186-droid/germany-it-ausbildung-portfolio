
# Subnetting Fundamentals and Exercises

## What is Subnetting?
Subnetting is the process of dividing a larger IP network into smaller subnetworks.

## Example 1: /24

Network: 192.168.1.0/24

- Subnet Mask: 255.255.255.0
- Network Address: 192.168.1.0
- Broadcast Address: 192.168.1.255
- First Usable IP: 192.168.1.1
- Last Usable IP: 192.168.1.254
- Usable Hosts: 254

## Example 2: /25

Network: 192.168.1.0/25

- Subnet Mask: 255.255.255.128
- Network Address: 192.168.1.0
- Broadcast Address: 192.168.1.127
- Usable Hosts: 126

## Example 3: Two /25 Subnets

Original network: 192.168.1.0/24

Subnet A:
- Network: 192.168.1.0/25
- Usable range: 192.168.1.1 – 192.168.1.126
- Broadcast: 192.168.1.127

Subnet B:
- Network: 192.168.1.128/25
- Usable range: 192.168.1.129 – 192.168.1.254
- Broadcast: 192.168.1.255

## Learning Outcome
I learned how to identify network addresses, broadcast addresses and usable host ranges in basic IPv4 subnets.
