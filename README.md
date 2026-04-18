# Nithesh VH — Digital VLSI & Hardware Security

> *RTL to GDSII · Post-Quantum Cryptography · FPGA Prototyping · Hardware Verification*

---

## About Me

I'm an Electronics and Communication Engineering student at **PES University, Bangalore** (B.Tech, 2023–2027), focused on the full digital VLSI stack — from RTL design and formal verification through physical implementation and tape-out flows.

My current research sits at the intersection of **hardware security** and **post-quantum cryptography**, where I design resource-efficient cryptographic cores for ASIC and FPGA targets. I also work on hardware accelerators for compute-intensive domains like bioinformatics and hardware verification.

---

## Research & Projects

### 🔐 Post-Quantum Secure JTAG Access Manager *(Nov 2025 – Mar 2026)*
**Hardware Security · FPGA & ASIC**

Built a post-quantum secure iJTAG access manager integrating:
- **ML-KEM (Kyber-512)** for key encapsulation
- **Ascon AEAD / Hash / PRF / MAC** for authenticated encryption
- **SRAM PUF with BCH ECC** for device-unique key generation
- Encrypted scan chain for secure DFT access

Proposed a **unified Ascon permutation architecture** that shares one core across six cryptographic operations — better area efficiency than standalone implementations.

---

### ⚙️ RTL to GDSII — Wally RISC-V Processor *(Aug 2025 – Present)*
**Processor Architecture · Cadence Toolchain**

- Designed a multi-cycle RISC-V processor supporting R, I, B, and S-type instructions
- Achieved full timing closure across all PVT corners using Cadence Genus + Innovus + Tempus
- Focused on control-path setup constraints; verified with waveform analysis in Xilinx Vivado

---

### 🧬 K-Mer Counting Hardware Accelerator *(Mar 2026)*
**Bioinformatics RTL · Verilog HDL**

- Synthesizable Verilog RTL accelerator for K-mer frequency counting from streaming DNA input
- Processes one base per clock cycle at **100 MHz** on Cadence SimVision
- Shift-register datapath with single-cycle read-modify-write counter memory
- 4-state FSM (IDLE → FILL → RUN → DONE); verified across **22/22 self-checking testbench cases** including error detection

---

### 🔒 RTL to GDSII — AES-128 Encoder *(Aug – Dec 2025)*
**Digital Design · Physical Implementation**

- Full RTL-to-GDSII flow on Cadence toolchain (Genus, Innovus, Tempus)
- Achieved **20–25% timing improvement** and **10–18% power reduction** via datapath optimization and clock gating

---

### 🤖 Micro Guardian: Autonomous Pest Detection Rover *(May – Jul 2025)*
**Computer Vision · Embedded Systems · Internship at CIOT**

- Six-wheeled rover with camera-based neural network for real-time pest detection
- Servo-controlled targeting system integrated with live inference pipeline

---

### 🛸 Aerial Survey of Martian Surface *(Nov – Dec 2024)*
**Autonomous Navigation Systems**

- Designed an autonomous quadcopter navigation system with dust storm resilience for simulated Martian survey conditions

---

## Technical Skills

| Domain | Tools & Technologies |
|---|---|
| **RTL Design** | SystemVerilog, Verilog HDL, SystemC |
| **Physical Design** | Cadence Innovus, Genus, Tempus, Calibre |
| **Formal Verification** | Cadence Jasper Gold |
| **FPGA** | Xilinx Vivado |
| **Simulation** | EDA Playground, LTspice, Cadence SimVision |
| **Languages** | Python, C |
| **Domains** | Post-Quantum Crypto, Low-Power Design, Hardware Security, STA |

---

## Education

**PES University**, Bangalore, Karnataka
B.Tech in Electronics and Communication Engineering
GPA: 7.66 / 10.0 · Aug 2023 – May 2027

---

## Certifications & Recognition

- 🥇 **Top 5 Finalist** — Spiral State-Level Hackathon, PES University (Aug 2024)
- 🏆 **Top 10** — Arithemania Hackathon, PES University (Dec 2025)
- Data Structures & Algorithms — Udemy (2024)
- AWS Introduction (2023)
- MySQL Bootcamp — Udemy (2024)

---

## Community

- **CAD Modelling Team** — IEEE Robotics and Automation Society, PES University *(Mar 2025 – Present)*
- **Scientific Researcher** — Equinox: The Space Club, PES University *(Nov 2024 – Present)*
- **Stage & Infrastructure Organizer** — Aatmatrisha & Samarpana Events *(Feb – Nov 2024)*

---

## Contact

📧 vhnithesh@gmail.com
📞 +91-99641-31906
🔗 [linkedin.com/in/nithesh-vh-00366728b](https://linkedin.com/in/nithesh-vh-00366728b)
📍 Bangalore, Karnataka, India

---

*Open to research collaborations, VLSI internships, and hardware security projects.*
