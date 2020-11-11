# Distributed Process Communication
Triditional operation system provides inter process communication to exchange data. There is no general mechanism for distributed environment.
This repository tries to provide similar mechanism for distributed environment. But it could not be exactly the same as IPC in a general distributed environment. For example, shared memory is the fastest IPC method. But the similiar idea RDMA often requires special hardware support and the usage is totally different. So I will not be working on any method which requires special hardware.

# Stage 1
Provide lock, conditional variable, semaphore, shared memory and simple queue. It has the similar semantics and interfaces as posix IPC. But the interfaces may will be changed in future.
