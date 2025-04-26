# NanoKV

**NanoKV** is a blazing-fast, lightweight key-value store written in C++.  
It features in-memory storage, durable append-only persistence (AOF), and a minimal TCP server interface — perfect for developers who need raw speed and simplicity.

##  Features
-  Ultra-fast in-memory key-value storage
-  TCP server interface (default port: `6379`)
-  Simple commands: `SET`, `GET`, `DEL`
-  Persistent storage via Append-Only File (`store.aof`)
-  Lightweight, developer-friendly, open-source

##  Build & Run

```bash
make
./nanokv
