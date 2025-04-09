# Lithops FLOPS Benchmark

This is a FLOPS (Floating Point Operations Per Second) benchmark tool built with [Lithops](https://lithops.cloud/) to measure distributed matrix multiplication performance in the cloud using Function-as-a-Service (FaaS).

It spawns multiple parallel workers that execute matrix multiplications and calculates the total FLOPS rate achieved by the system.

Inspired by HPC benchmarking tools, this is useful for testing and comparing performance across different cloud providers or backends supported by Lithops.

---

## How to Run

To execute the benchmark, simply run the following command:

```bash
python3 flops_benchmark.py
```