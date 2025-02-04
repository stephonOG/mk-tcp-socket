#Network Programming: TCP Socket Connection

This project is part of my network programming learning journey. It demonstrates how to create a simple TCP client that connects to a remote server by resolving the hostname to an IP address and verifying the port number before attempting the connection.

## Overview

This script uses Python's `socket` library to establish a connection between a client and a remote server over TCP. It covers the following concepts:

- **Socket creation**: Setting up a socket for communication.
- **Port validation**: Ensuring the port number is valid.
- **Hostname resolution**: Resolving a given hostname to an IP address.
- **Remote server connection**: Connecting to a server over TCP and handling errors during the connection process.
- **Socket closure**: Closing the socket after the communication attempt.

## Features

- **Socket Creation**: The script creates a TCP socket using the IPv4 address family.
- **Port Number Validation**: It ensures that the entered port number is any number from 1-65535.
- **Hostname Resolution**: The script resolves the given hostname to an IP address using DNS lookup.
- **Error Handling**: It gracefully handles errors during socket creation, hostname resolution, and connection attempts.

## Prerequisites

- Python
- Basic understanding of networking concepts, such as IP addresses, ports, and TCP communication.

## How to Run

1. Clone or download this repository to your local machine.
2. Open your terminal or command prompt.
3. Navigate to the project directory.
4. Run the script:
   ```bash
   python mksocket.py
