# Hashes Calculation Benchmark for Rendezvous Hashing

This repository contains a benchmarking study comparing different hash combining methods for rendezvous hashing. The code evaluates various approaches to optimize the performance of hash calcualtion for rendezvous hashing while maintaining good distribution properties.

## Overview

The main notebook (`main.ipynb`) implements and tests several hash combining strategies:

- Simple multiplication
- Jenkins hash combination 
- FNV-1a inspired combination
- And more (commented out in code)

The implementation focuses on 32-bit MurmurHash as the base hashing function while exploring different ways to efficiently combine server and key hashes.

## Key Features

- Comprehensive benchmarking of different hash combining methods
- Analysis of key distribution properties
- Statistical evaluation including standard deviation and skewness
- Performance comparison between baseline and optimized approaches
- Visualization of distribution results

## Usage

1. Clone the repository
2. Install dependencies
3. Run the Jupyter notebook to see benchmarks and analysis

## Learn More

The full analysis and discussion of results is available in the accompanying article: [Rendezvous Hashing: The Path to Faster Hashes Calculation](https://www.npiontko.pro/2024/12/23/computation-efficient-rendezvous-hashing)

## License

[MIT License](LICENSE)

