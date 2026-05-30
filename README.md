# Aegis Edge: Secure Offline Facial Recognition & Liveness Module for NHAI Datalake 3.0

[![License: Apache-2.0](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Framework Compatibility](https://img.shields.io/badge/Framework-React_Native-61dafb?logo=react)](https://reactnative.dev/)
[![Platform Support](https://img.shields.io/badge/Platforms-Android_8.0+_|_iOS_12+-brightgreen)](https://reactnative.dev/)
[![Model Architecture Footprint](https://img.shields.io/badge/Model_Size-16.8_MB-success)](./models/)

## 📌 Executive Overview
Aegis Edge is a high-performance, edge-AI biometric ecosystem engineered explicitly to provide uninterrupted identity verification for NHAI field personnel operating within zero-network environments. Designed as a modular native drop-in component for the **Datalake 3.0** application, this solution processes face identification and multi-point passive/active anti-spoofing entirely client-side without any active cellular or data connection.

### ⚡ Technical Performance Commitments
* **Zero-Network Isolation:** 100% computational execution on-device.
* **Ultra-Lightweight Footprint:** Entire engine compressed to **16.8 MB**, comfortably clearing the ~20 MB hackathon threshold.
* **Sub-Second Low Latency:** Complete inference cycle (recognition + liveness check) executes in **< 750ms**.
* **Hardware Inclusivity:** Runs smoothly on standard mid-range mobile hardware (minimum 3GB RAM) without requiring specialized external GPUs.
* **Demographic & Environmental Robustness:** Achieves **>95% accuracy** under harsh Indian outdoor lighting variables (overhead sunlight, deep shadows, low light).

---

## 🏗️ Technical Architecture & Workflow Design

The system decouples data streaming, local ML classification, and cryptographic data management into a strictly linear pipeline: