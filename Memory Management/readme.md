# Memory Management

Low-level languages like C, have manual memory management primitives such as malloc() and free(). 
In contrast, JavaScript automatically allocates memory when objects are created and frees it when they are not used anymore (garbage collection). 
This is why JavaScript is a garbage-collected language.

JavaScript removes the pain of memory management by automatically allocating its memory and freeing it up (garbage collection) when not in use. 
It is important to know memory management, if we know how JavaScript allocates its memory, then we will be able to use the memory optimally and effectively. Again if we understand how JavaScript runs the garbage collection algorithm, then we can settle some of the memory leakages which may arise.



## What is memory management?
The practice of managing and coordinating memory in your software is known as memory management. It makes sure that memory blocks are correctly managed and distributed so that the application and other processes that are currently running have the memory they require to complete their tasks.


* [Memory Life Cycle](/Memory%20Management/memory_cycle.md)