# 👋 Hi, I'm Pallavi Behura

### 💻 Prefinal-Year B.Tech ECE | VLSI & RTL Design | AI/ML Hardware | Computer Architecture | DSP Accelerators

I'm a **Prefinal-Year Electronics & Communication Engineering student** focused on **VLSI/RTL design, digital hardware, computer architecture, and AI/ML hardware acceleration**.

I’m most interested in building and evaluating hardware: from RTL and verification to processor-based SoCs, DSP accelerators, mixed-precision datapaths, and hardware/software co-design. **RF and antenna engineering remain secondary ECE interests** in my broader project portfolio.

---

## 💫 About Me

🔹 Primary focus: **VLSI, RTL design, digital hardware, and verification**

🔹 Exploring **AI/ML hardware, quantization, fixed-point arithmetic, and accelerator architecture**

🔹 Interested in **RISC-V, computer architecture, AMBA bus protocols, and hardware/software co-design**

🔹 Building with **Verilog, SystemVerilog, Python, and FPGA/EDA workflows**

🔹 RF, antennas, and embedded systems remain supporting interests

🔹 I learn by **building → simulating → debugging → analyzing → improving**

### 🚀 Currently Exploring

💻 VLSI / RTL Design & Verification
🧠 Computer Architecture & RISC-V SoCs
⚡ DSP and Hardware Accelerators
🤖 AI/ML Hardware & Quantization
🔗 Hardware/Software Co-Design
🧪 FPGA Synthesis, Timing & PPA Analysis
🔌 Embedded Systems
📡 RF & Antenna Engineering (secondary)

---

# 🛠️ Tech Stack

### 👩‍💻 Programming & HDL

![C](https://img.shields.io/badge/C-%2300599C.svg?style=for-the-badge\&logo=c\&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-%2300599C.svg?style=for-the-badge\&logo=c%2B%2B\&logoColor=white)
![Python](https://img.shields.io/badge/Python-%233670A0.svg?style=for-the-badge\&logo=python\&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-%23e16737.svg?style=for-the-badge\&logo=mathworks\&logoColor=white)
![Verilog](https://img.shields.io/badge/Verilog-%23B2B7F8.svg?style=for-the-badge\&logo=verilog\&logoColor=black)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-%23007ACC.svg?style=for-the-badge\&logoColor=white)

### 📊 Scientific Computing & AI/ML

![Jupyter](https://img.shields.io/badge/Jupyter-%23F37626.svg?style=for-the-badge\&logo=jupyter\&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-%23013243.svg?style=for-the-badge\&logo=numpy\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-%23150458.svg?style=for-the-badge\&logo=pandas\&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge\&logo=scipy\&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-%23FF0100.svg?style=for-the-badge\&logo=opencv\&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-%23009688.svg?style=for-the-badge\&logo=google\&logoColor=white)

`Machine Learning` `Random Forest` `Computer Vision` `Object Tracking` `Signal Processing` `Data Analysis` `Intelligent Systems`

### 📡 RF / Antennas / EDA

![HFSS](https://img.shields.io/badge/ANSYS_HFSS-%23FFB71B.svg?style=for-the-badge\&logo=ansys\&logoColor=black)
![FEKO](https://img.shields.io/badge/Altair_FEKO-%23E41E25.svg?style=for-the-badge\&logo=altair\&logoColor=white)
![Cadence](https://img.shields.io/badge/Cadence_EDA-%23C01818.svg?style=for-the-badge\&logoColor=white)

`Antenna Design` `RF & Microwave` `Electromagnetics` `Vivaldi` `SIW` `RIS` `Array Analysis` `Beam Steering` `Phase Quantization`

### 🔌 Embedded / Development

![ESP32](https://img.shields.io/badge/ESP32-%23E7352C.svg?style=for-the-badge\&logo=espressif\&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-%2300979D.svg?style=for-the-badge\&logo=arduino\&logoColor=white)
![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=for-the-badge\&logo=git\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge\&logo=github\&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-%23007ACC.svg?style=for-the-badge\&logo=visual-studio-code\&logoColor=white)

---

# 🎯 Current Internship Focus

I'm currently prioritizing **VLSI/RTL design, design verification, digital hardware, computer architecture, DSP accelerators, and AI/ML hardware**. The projects below are ordered by their relevance to those roles and the strength of the documented implementation and verification evidence.

---

# 🚀 Selected Projects

## 1. 4096-Point FFT/IFFT Accelerator

**RTL • DSP Architecture • Clock Gating • CORDIC • PPA Optimization**

A continuous-flow 4096-point FFT/IFFT design with RTL variants, a reference model, verification infrastructure, synthesis scripts, and reports. The repository reports **15/15 functional tests**, alongside baseline comparisons for latency, area, SQNR, and power under a documented 45 nm synthesis flow.

🔗 [**View Repository →**](https://github.com/pallavibehurageek-cyber/Jointly-Optimized-Continuous-Flow-4096-Point-FFT-IFFT-Accelerator)

---

## 2. RISC-V SoC + Custom ML Accelerator

**RISC-V • Verilog • AXI4-Lite • APB • Q4.4 Fixed-Point • Bare-Metal Firmware**

A processor-based SoC integrating a PicoRV32 RV32IM core, AXI4-Lite-to-APB interconnect, BRAM, a fixed-point matrix-multiplication accelerator, APB UART, and bare-metal firmware. The repository documents FPGA timing results, including a reported 158 MHz maximum frequency and positive timing slack.

🔗 [**View Repository →**](https://github.com/pallavibehurageek-cyber/RISC-V-SoC-Custom-ML-Accelerator)

---

## 3. EvoFFT — Stage-Wise Mixed-Precision FFT Optimizer

**Verilog • Python • NSGA-II • Mixed Precision • FPGA-Oriented Optimization**

Explores stage-wise FP4/FP8 arithmetic choices and multi-objective design-space exploration for FFT architectures, balancing signal quality against hardware costs such as area, power, and latency.

🔗 [**View Repository →**](https://github.com/pallavibehurageek-cyber/EvoFFT-StageWise-MixedPrecision-FFT-Optimizer)

---

## 4. AXI4-Lite Programmable PWM IP Core

**Verilog • AXI4-Lite • FSMs • Memory-Mapped Registers • Self-Checking Testbench**

A synthesizable memory-mapped peripheral with configurable PWM timing, breathing mode, status handling, interrupt generation, byte-strobe support, and simulation waveform captures.

🔗 [**View Repository →**](https://github.com/pallavibehurageek-cyber/AXI4-Lite-Programmable-PWM-Peripheral-IP-Core)

---

## 5. SystemVerilog APB RAM + Verification

**SystemVerilog • AMBA APB • Testbench Architecture • Functional Verification**

An APB-based RAM peripheral with a structured verification environment using transaction generation, driving, monitoring, and expected-versus-observed checks, plus an FPGA-oriented synthesis flow.

🔗 [**View Repository →**](https://github.com/pallavibehurageek-cyber/SV-APB-RAM-RTL-Design-Verification)

---

## AI/ML Hardware Research — Work in Progress

### Hessian-Guided BFP2 Quantization & Channel-Scatter Accelerator

**SystemVerilog • PyTorch • 2-Bit Block Floating Point • Quantization-Aware Evaluation**

An exploration of low-bit neural-network weight grouping and a channel-scatter hardware datapath. The repository documents ongoing verification and important numerical limitations in the default pair-level routing configuration; software-model accuracy figures should **not** be presented as hardware-verified end-to-end accuracy.

🔗 [**View Repository →**](https://github.com/pallavibehurageek-cyber/Hessian-Guided-BFP2-Quantization-Accelerator)

---

## Additional RTL Projects

These projects provide supporting examples of digital design, interface logic, and verification:

- [**Weighted Round-Robin Arbiter**](https://github.com/pallavibehurageek-cyber/Weighted-Round-Robin-Arbiter-Verilog) — credit-based arbitration and grant logic.
- [**8-bit UART Communication System**](https://github.com/pallavibehurageek-cyber/8-bit-RTL-UART-Communication-System) — transmitter/receiver RTL with loopback testbench.
- [**RISC-MIPS32 CPU**](https://github.com/pallavibehurageek-cyber/RISC-MIPS32-CPU-Verilog) — five-stage pipelined processor design.
- [**128-Point Fixed-Point FFT Accelerator**](https://github.com/pallavibehurageek-cyber/128-Point-Fixed-Point-FFT-Hardware-Accelerator) — RTL and testbench are present; simulation and numerical verification are still pending in its README.

---

## Other ECE Work

RF/antenna and embedded projects remain available, but are not the main focus of this internship-oriented shortlist:

- [10 GHz Vivaldi Antenna](https://github.com/pallavibehurageek-cyber/10GHz-Vivaldi-Antenna-HFSS)
- [SIW Slot Antenna](https://github.com/pallavibehurageek-cyber/hfss-substrate-integrated-waveguide-antenna)
- [Gesture-Based Vehicle Control](https://github.com/pallavibehurageek-cyber/Gesture-Based-Vehicle-Control)
- [EOG-Based Real-Time Eye Tracking](https://github.com/pallavibehurageek-cyber/EOG-Based-Real-Time-Eye-Tracking)
- [Extended Kalman Object Tracking](https://github.com/pallavibehurageek-cyber/extended-kalman-object-tracking)

[**Explore All My Repositories →**](https://github.com/pallavibehurageek-cyber?tab=repositories)

---

# 📊 GitHub Stats

<p align="center">
  <img
    height="170"
    src="https://github-readme-stats.vercel.app/api?username=pallavibehurageek-cyber&show_icons=true&include_all_commits=true&count_private=false&rank_icon=github&theme=tokyonight&hide_border=true&custom_title=Pallavi%27s%20GitHub%20Stats"
    alt="GitHub Stats"
  />
  <img
    height="170"
    src="https://streak-stats.demolab.com/?user=pallavibehurageek-cyber&theme=tokyonight&hide_border=true&mode=daily"
    alt="GitHub Streak"
  />
</p>

---

# 🥧 Languages I've Used

<p align="center">
  <img
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=pallavibehurageek-cyber&layout=pie&langs_count=10&theme=tokyonight&hide_border=true&custom_title=Languages%20I%27ve%20Used&exclude_repo=pallavibehurageek-cyber"
    alt="Languages I've Used"
  />
</p>

<p align="center">
  <i>Automatically generated from code in my public GitHub repositories.</i>
</p>

---

# 🌐 Connect With Me

<p align="center">

<a href="https://github.com/pallavibehurageek-cyber">
<img src="https://img.shields.io/badge/GitHub-%23181717.svg?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="https://linkedin.com/in/pallavi-behura-547329214">
<img src="https://img.shields.io/badge/LinkedIn-%230A66C2.svg?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

</p>

---

# ✍️ Engineering Quote

<p align="center">
  <img
    src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight"
    alt="Engineering Quote"
  />
</p>

---

# ⚡ My Engineering Philosophy

<p align="center">

### BUILD → SIMULATE → ANALYZE → LEARN → IMPROVE

</p>

<p align="center">

### 🚀 Exploring. Building. Learning. Innovating.

</p>

---

<!--
=========================================================
                     CONFIGURATION
=========================================================

GITHUB USERNAME
---------------------------------------------------------
pallavibehurageek-cyber


VISUAL THEME
---------------------------------------------------------
Primary analytics theme:
tokyonight

Used for:
- GitHub Stats
- GitHub Streak
- Language Pie
- Engineering Quote


GITHUB STATS
---------------------------------------------------------
Service:
https://github-readme-stats.vercel.app/

Current:
show_icons=true
include_all_commits=true
count_private=false
rank_icon=github
theme=tokyonight
hide_border=true

Optional:
hide=issues,prs


LANGUAGE PIE
---------------------------------------------------------
Service:
https://github-readme-stats.vercel.app/

Current:
layout=pie
langs_count=10
theme=tokyonight
hide_border=true

The profile README repository is excluded:
exclude_repo=pallavibehurageek-cyber

Add more repositories to exclude with:
exclude_repo=repo1,repo2


GITHUB STREAK
---------------------------------------------------------
Service:
https://streak-stats.demolab.com/

Current:
theme=tokyonight
hide_border=true
mode=daily


WHY THERE IS NO TROPHY WIDGET
---------------------------------------------------------
The public GitHub Profile Trophy deployment has had
403/503/deployment-paused problems, so it has intentionally
been removed rather than using an unstable third-party mirror.


WHY THERE IS NO ACTIVITY GRAPH
---------------------------------------------------------
The public github-readme-activity-graph Vercel deployment
is currently returning HTTP 402 because the upstream
deployment is billing-locked/paused.

It has intentionally been removed.


PROJECT MAINTENANCE
---------------------------------------------------------
When a stronger project is completed:

1. Add it to the correct domain.
2. Add it to "More Projects".
3. Promote it to "Selected Projects" if it becomes
   one of your strongest repositories.
4. Replace the weakest featured project.

Keep:
"Explore All My Projects"

permanently.

=========================================================
-->
