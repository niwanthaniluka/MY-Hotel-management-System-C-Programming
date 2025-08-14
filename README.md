# Hotel Management System (C)

![Hotel Management System banner](image.png)



A simple, file-based hotel management system written in C. It helps manage rooms, guests, and bookings from a terminal interface.

## Features
- Book a room
- View Customer Record
- Delete Customer Record
- Search Customer Record
- Edit Record
- Cross-platform: Linux, macOS, Windows (MinGW)

## Quick Start

1) Clone
- git clone https://github.com/your-niwanthaniluka/hotel-management-c.git
- cd hotel-management-c

2) Build
- Linux/macOS:
  gcc -std=c11 -Wall -Wextra -O2 src/*.c -o hms
- Windows (MinGW):
  gcc -std=c11 -Wall -Wextra -O2 src\*.c -o hms.exe

3) Run
- ./hms
- or on Windows: hms.exe

Data files are saved under data/ by default.

## Project Structure
- src/       C source files (main.c, rooms.c, guests.c, bookings.c, utils.c)
- include/   Headers (rooms.h, guests.h, bookings.h, utils.h)
- data/      CSV storage (rooms.csv, guests.csv, bookings.csv)
- assets/    Images (image.png)
- README.md

## Sample UI
