### Web Proxy

This project contains a custom implementation of a web proxy that acts as an intermediary between clients making requests and the web servers that satisfy them. The system provides functional support for receiving incoming connections, parsing HTTP requests, forwarding them to target servers, and returning server responses back to the corresponding client. The implementation supports multiple concurrent requests through a multi-threaded architecture. 

#### Performance Data

* Achieved maximum correctness score across 35 unique test traces checking basic proxy operations, robustness, compliance and high-concurrency scenarios.

#### Development and Tools

* Language: C
* Platform: Linux x86-64
* Libraries: POSIX Threads, Robust I/O package, specialized HTTP string parsing library
* Debugging: GDB and valgrind

#### Academic Integrity Statement

In compliance with Carnegie Mellon University academic integrity policies, the source code for this project is maintained in a private repository. I am available to discuss the specific data points, performance results, and engineering trade-offs encountered during the development of this concurrent web proxy.
