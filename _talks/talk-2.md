---
title: "Performance Evaluation of IoT Encryption Algorithms: Memory, Timing, and Energy"
collection: talks
type: "Talk"
permalink: /talks/talk-2
venue: "Annual Student Research and Creative Endeavors Exhibition"
date: 2019-04-17
location: "Mount Pleasant, Michigan"
---

Security in the Internet of Things is a crucial aspect and a lot of studies are focused on modular and scalable encryption algorithms. Resource constraints at the edge nodes of an IoT network require lightweight encryption algorithms. A popular symmetric encryption algorithm is the Advanced Encryption System or AES for short. However, AES encryption/decryption can impose large computation demands on resource constrained IoT devices.

In this talk, I present a comparative study of AES with and without hardware accelerators and eXtended Tiny Encryption Algorithm (XTEA), which is a lightweight encryption algorithm suited for resource constrained devices. I analyze the performance of AES and XTEA in terms of memory, power and execution time and assess the feasibility of using XTEA in low resource embedded platforms. Although the hardware accelerated AES was fastest (0.5 ms) and consequently required the least amount of energy (0.01 mJ) out of the three, the execution time (1.25 ms) and energy consumed (0.024 mJ) by XTEA was comparatively close and can be a feasible encryption algorithm for low resource microcontrollers that do not have the resources to support AES implementation in software or lack a hardware accelerator. Software implementation of AES on 8-bit PIC architecture required 7538 bytes whereas XTEA required only 1184 bytes of program memory, leaving enough space for application firmware.