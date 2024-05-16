# xv7 - A C++ re-implementation of xv6

## Project Overview
This is a UNIX kernel programming passion project. The hope is to gain hands on system programming experience by re-creating a lightweight OS called xv6.
Obviously, I want to add my own twist and make my life harder, which is why I want to re-implement xv6 in C++. This will help me understand whether an
object-oriented language like C++ makes sense in terms of buliding an OS. This might sound stupid, but projects are meant to be fun and stupid, especially my projects! Below is the roadmap and what I would gain throughout the development of this project.

### What is xv6?
[xv6](https://github.com/mit-pdos/xv6-public) is a re-implementation of Dennis Ritchie's and Ken Thompson's Unix Version 6 (v6). xv6 loosely follows the structure and style of v6, but is implemented for a modern x86-based multiprocessor using ANSI C.

### What is xv7?
xv6 with C++ (plus plus) is xv7. Did you get it? Haha...

### Roadmap

- [x] Read through Operating Systems: Three Easy Pieces and xv6 manual
- [x] Completely understand the xv6 source code line by line
- [ ] Work on xv6 exercises and OSTEP projects
- [ ] Starting designing xv7
- [ ] Implement xv7
- [ ] Convert build system to CMake
- [ ] Benchmark xv6 vs xv7 using LMBench
#### Stretch goals
- [ ] Write a network stack
- [ ] Re-implement xv7 base on ARM architecture

### What I expect to learn from this project
* How an OS works?
    * how an OS boots
    * CPU virtualization
    * Memory virtualization
    * Concurrency
    * Filesystem
    * Device drivers
        * char, block, and net drivers
* C and C++ programming
* Whether OOP makes sense for an OS
* x86 architecture
* make and CMake
* GCC and GDB
* How to benchmark an OS

### Resources I would be using
* [Operating Systems: Three Easy Pieces](https://pages.cs.wisc.edu/~remzi/OSTEP/)
* [xv6 manual](https://pdos.csail.mit.edu/6.828/2018/xv6/book-rev11.pdf)
* [xv6 source code](https://github.com/mit-pdos/xv6-public)
* [Operating Systems: Three Easy Pieces Projects](https://github.com/remzi-arpacidusseau/ostep-projects/)

### Acknowledgements

The code in the files that constitute xv6 is
Copyright 2006-2018 Frans Kaashoek, Robert Morris, and Russ Cox.
