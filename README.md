# Linux Device Drivers

> Linux Device Drivers: Where the Kernel Meets the Hardware, 3rd Edition, by Jonathan Corbet, Alessandro Rubini, and Greg Kroah-Hartman
>
> |Publication date|Print length|
> |-|-|
> |March 15, 2005|636 pages|

## Preface

- This is, on the surface, a book about writing device drivers for the Linux system.

- But this book is also about how the Linux kernel works and how to adapt its workings to your needs or interests.

- This edition covers the 2.6.10 kernel as completely as we are able.

### Audience for This Book

- This book should be an interesting source of information both for people who want to experiment with their computer and for technical programmers who face the need to deal with the inner levels of a Linux box.

- We hope this book is useful as a starting point for people who want to become kernel hackers but don't know where to start.

- This book does not cover the Linux kernel in its entirety, of course, but Linux device driver authors need to know how to work with many of the kernel's subsystems.

- If you don't want to go deep into the details, you can just skip the most technical sections, and stick to the standard API used by device drivers to seamlessly integrate with the rest of the kernel.

### Organization of the Material

- The book introduces its topics in ascending order of complexity and is divided into two parts.

- The first part (Chapters 1-11) begins with the proper setup of kernel modules and goes on to describe the various aspects of programming that you'll need in order to write a full-featured driver for a char-oriented device.

- Every chapter covers a distinct problem and includes a quick summary at the end, which can be used as a reference during actual development.

- Throughout the first part of the book, the organization of the material moves roughly from the software-oriented concepts to the hardware-related ones.

- Every chapter includes source code and points to sample drivers that you can run on any Linux computer.

- The second half of the book (Chapters 12-18) describes block drivers and network interfaces and goes deeper into more advanced topics, such as working with the virtual memory subsystem and with the PCI and USB buses.

### Background Information

- In order to be able to use this book, you need to be confident with C programming.

- Some Unix expertise is needed as well, as we often refer to Unix semantics about system calls, commands, and pipelines.

- Several free software tools are needed to build the kernel, and you often need specific versions of thses tools.

- Tool version requirements vary from one kernel to the next; consult *Documentation/Changes* in the source tree of the kernel you are using for exact requirements.

### Online Version and License

- The authors have chosen to make this book freely available under the Creative Commons “Attribution-ShareAlike” license, Version 2.0:

## Contents

- [x] [1. An Introduction to Device Drivers](01-an-introduction-to-device-drivers.md) ... 1

- [ ] 2. Building and Running Modules ... 15

- [ ] 3. Char Drivers ... 42

- [ ] 4. Debugging Techniques ... 73

- [ ] 5. Concurrency and Race Conditions ... 106

- [ ] 6. Advanced Char Driver Operations ... 135

- [ ] 7. Time, Delays, and Deferred Work ... 183

- [ ] 8. Allocating Memory ... 213

- [ ] 9. Communicating with Hardware ... 235

- [ ] 10. Interrupt Handling ... 258

- [ ] 11. Data Types in the Kernel ... 288

- [ ] 12. PCI Drivers ... 302

- [ ] 13. USB Drivers ... 327

- [ ] 14. The Linux Device Model ... 362

- [ ] 15. Memory Mapping and DMA ... 412

- [ ] 16. Block Drivers ... 464

- [ ] 17. Network Drivers ... 497

- [ ] 18. TTY Drivers ... 546

- Bibliography ... 575

- Index ... 579
