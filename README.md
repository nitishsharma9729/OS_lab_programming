# CEC301 — Operating Systems Lab Manual (Python)

A complete collection of Python implementations and simulations for the **CEC301 Operating Systems Lab**. This repository covers Linux system calls, multithreading, CPU scheduling, process synchronization, deadlock avoidance, memory management, disk scheduling, and file allocation.

---

## 📋 List of Programs

| S.No. | Title of Program | Key Concepts / Python Modules |
| :---: | :--- | :--- |
| **1** | **Introduction to Linux System Calls** | Process creation and control using `os.fork()`, `os.exec*()`, and `os.wait()` |
| **2** | **Thread Creation and Management** | Multithreading using Python's `threading` module |
| **3** | **CPU Scheduling Algorithms** | FCFS, SJF, Priority Scheduling, and Round Robin (RR) |
| **4** | **Process Synchronization (Producer-Consumer)** | Bounded-buffer synchronization using `threading.Semaphore` |
| **5** | **Process Synchronization (Readers-Writers)** | Concurrent read/write synchronization using Semaphores & Locks |
| **6** | **Dining Philosophers Problem** | Resource sharing and deadlock prevention using `threading.Semaphore` |
| **7** | **Deadlock Avoidance** | Safe-state detection and resource allocation using Banker's Algorithm |
| **8** | **Contiguous Memory Allocation** | First Fit, Best Fit, and Worst Fit strategies |
| **9** | **Page Replacement Algorithms** | FIFO, Least Recently Used (LRU), and Optimal page replacement |
| **10** | **Disk Scheduling Algorithms** | FCFS, SSTF, SCAN, and C-SCAN head movement |
| **11** | **File Allocation Methods** | Contiguous, Linked, and Indexed file allocation |

---

## 🚀 How to Run

1. **Run any Python script:**
   ```bash
   python3 DU_OS_Lab_Manual_Python2.ipynb
   ```

> **Note:** Program 1 (`os.fork()`) requires a POSIX-compliant environment such as Linux, macOS, or Windows Subsystem for Linux (WSL). All other simulations run cross-platform.

---

## 🛠️ Environment & Requirements
* **Language:** Python 3.x
* **Standard Libraries Used:** `os`, `sys`, `threading`, `time`, `random`
* **Operating System:** Linux (Ubuntu / Debian / WSL)
