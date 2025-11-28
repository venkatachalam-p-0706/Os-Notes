

It is an intermediary software/program between the user of the computer and hardware of the computer.


Early operating systems focused only on managing hardware resources
**Are all operating systems compatible with all types of hardware?**
Operating systems are designed to work with specific hardware architectures. It's important to choose an operating system that is compatible with your hardware.
#### General Tasks carried by OS 

1. Handling UI
2. Handling input/output
3. Process management
4. File Management
5. Memory Management
6. Security
7. other devices control like printer, SD card
### Goals:
Execute user programs and make problem solving easier.
Make the computer convenient to use
Use the computer hardware in an efficient manner.

### Four components:
- User
- Application Programs
- Operating System
- Hardware
Users(Humans, machines, other computers) use Application programs(which define the way in which the computer resources are used to solve computing problems of the user) through Operating Systems(which coordinate hardware resources among various users and application programs)
that run on the  Hardware (which provides computing resources such as I/O devices , RAM, ROM etc... )

### Users:
- Are abstracted from the resource utilization and they really don't care about how the resources are distributed among different application programs.
- All they need is just performance and the function of the OS is to give that.
- Shared computers such as mainframe computers and minicomputers must keep all users happy
- Handheld computers(Laptops in general and also devices like Raspberry Pi) are more inclined to efficient battery management and performance to a certain level.
- Workstations have their own resources but often depend on the servers for shared resources
- A mainframe is a powerful, high-performance computer used by large organizations for critical applications like massive data processing, transaction processing, and enterprise resource planning 
- A workstation is **a special computer designed for technical or scientific applications**. Intended primarily to be used by a single user, they are commonly connected to a local area network and run multi-user operating systems.
- Handheld computer such as raspberry pi are  resource poor which also leads to poor performance. They are optimized for usability and battery life

### Function of OS
#### Resource allocation:
Manages all resources
Decides between conflicting requests for efficient and fair resource use
#### Controls Programs:
Controls execution of programs to prevent errors and improper use of the computer


"The one program running at all times on the computer"
is the kernel. Everything else - sys progs or apps

Firmware is a type of permanent software programmed directly into a device's read-only memory (ROM) or flash memory. Booting Programs such as BIOS are stored in here.

OS provides Dual Mode : User and Kernel mode. Mode Bit is used to identify/defines in which mode the operating system is in.

In most operating systems and CPU architectures:
Kernel mode is represented by 0. Some programs are executable only in kernel and are often considered "privileged"
User mode is represented by 1

System call changes mode to kernel, return from call resets it to user. In other words, systems calls are always handled by kernel.
CPUs support multi-mode operations i.e. virtual machine manager (VMM) mode for guest VMs.
Virtual machine manager in simple words is just a software that simulates a computer inside a computer. Using it we will be able to use and experience different OSes

The OS uses a timer to make sure no program runs forever or uses too many resources.

Before running a program, the OS sets a timer.
As time passes, the timer counts down.
When the timer hits zero, the OS gets an interrupt (a signal).
The OS can then:
Stop the program if it's been running too long
Or switch to another program (this is called scheduling)

![System Call](System%20Call.png)


### Evolution of OS
- OS will evolve over a period of time for a number of reasons:
- New features and services demanded by the users
- To be on par with the upgraded hardware
### Types of OS

#### Batch Systems - Groups jobs that perform similar type of function. These groups are treated as a batch and are executed at the same time;
##### 1)Simple Batch System
User had no direct access to the machine
Submits a job to the operator who then adds it to the job queue. 
Jobs are often batched together and the entire batch is placed in the input device
JCL (Job Control Language ) - Special Programming language to provide instructions to the monitor

### Common System Components:
Process Management
Main memory Management
File Management
I/o Management
Secondary Storage Management
Network
Protection
Command Interpreter