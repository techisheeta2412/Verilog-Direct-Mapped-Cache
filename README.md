# Direct-Mapped Cache with Write-Through Policy using Verilog

## Project Overview

This project focuses on the design and simulation of a direct-mapped cache memory system using Verilog.

The cache acts as an intermediate memory between the CPU and main memory to reduce memory access time.

A write-through policy is used to update both the cache and main memory during write operations.

## Key Features

- Direct-mapped cache architecture
- Cache hit and cache miss detection
- Write-through policy
- Tag and index comparison
- Valid-bit checking
- Memory interface
- Finite State Machine based control
- Verilog testbench validation

## Design Architecture

The system consists of:

- CPU interface
- Cache controller
- Tag comparator
- Address decoder
- Cache memory
- Main memory interface

The CPU generates a memory address. The address is divided into tag, index and offset fields.

The cache controller checks the tag and valid bit to determine whether the requested data is available in the cache.

## Cache Read Operation

During a read operation, the cache controller checks the cache line.

If the tag matches and the valid bit is active, a cache hit occurs and the data is returned from the cache.

If the data is not available, a cache miss occurs. The data is fetched from main memory and the cache line is updated.

## Write-Through Policy

During a write operation, the data is written to both the cache and main memory.

This helps maintain data consistency between the cache and main memory.

## Tools and Technologies

- Verilog HDL
- Digital System Design
- Finite State Machine
- EDA Playground
- Verilog Testbench
- Digital Simulation

## My Contribution

I worked on understanding the direct-mapped cache architecture, address partitioning and cache hit/miss logic.

I contributed to the study of the cache controller, tag comparison, valid-bit checking and write-through memory operation.

I also worked on simulation-based validation and understanding the read and write behaviour of the cache system.

## Key Learning

This project helped me understand:

- Cache memory architecture
- Verilog-based digital design
- Memory interfacing
- FSM-based control logic
- Cache hit and miss conditions
- Hardware simulation and testing

## Applications

Cache memory concepts are used in:

- Microprocessors
- Embedded processors
- System-on-Chip designs
- FPGA-based systems
- High-performance digital systems

## Project Documentation

The complete project report is available in this repository.
