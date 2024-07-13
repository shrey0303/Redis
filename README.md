# Redis with C++ from scratch

 This projects follows principles from [Build Your Own X From Scratch](https://build-your-own.org/) series of books. It covers fundamental aspects such as handling basic data types, client-server communication, and storage mechanisms.

## Build and Run

To make the compilation process more convenient, scripts have been provided in the `scripts` folder.

For windows compile the server and client manually

**IMPORTANT NOTE**: you need the install the dependencies of c++ compiler first, you can do that by running the following command:
  ```bash
  sudo apt-get install g++
  ```

<br>

**Compile Server and Client**
```bash
./scripts/compiler.sh
```	
the output files will be on folder `./outputs`.

<br>

**Run Server.**
```bash
./output/server
```

**Run Client.**
```bash
./output/client
```

