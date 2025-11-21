# CSE233 Assignment 2 – Process Management

## Overview
This project demonstrates:
- Process creation using `fork()`
- Shell process control (start, stop, resume, terminate)
- Linker and loader behavior in C programs

## Build
make

## Run
make run-process_creation
make run-output_program
make run-simple_program

## Shell Exercises
sleep 300 &
jobs
ps aux | grep sleep
kill <PID>
kill -STOP <PID>
kill -CONT <PID>

## Inspect Loader
ldd ./simple_program

## Clean
make clean

## License
MIT License (see LICENSE file)
