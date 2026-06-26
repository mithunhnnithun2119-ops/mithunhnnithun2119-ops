<div align="center">

<!-- Animated Header -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1a2e,100:16213e&height=200&section=header&text=Mithun%20H%20N&fontSize=60&fontColor=00d4ff&fontAlignY=38&desc=Embedded%20Systems%20Engineer%20%7C%20C%20%7C%20IoT%20%7C%20Hardware%20%2B%20Software&descAlignY=58&descSize=18&descColor=a0a0a0&animation=fadeIn"/>

<!-- Typing Animation -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=00D4FF&center=true&vCenter=true&width=600&lines=Embedded+Systems+Engineer+%F0%9F%94%A7;Advanced+C+%26+C%2B%2B+Developer+%F0%9F%92%BB;Hardware+%2B+Software+Enthusiast+%F0%9F%9A%80;IoT+%26+Microcontroller+Expert+%F0%9F%A4%96;Building+from+Bits+to+Systems+%E2%9A%A1" alt="Typing SVG" />
</a>

<br/>

<!-- Badges -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mithun-hn)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mithunhnnithun2119-ops/mithunhnnithun2119-ops)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mithunhnmithun2119@gmail.com)

</div>

---

## 🧠 About Me

```c
/* mithun.c - Who I am */

#include <stdio.h>
#include <passion.h>
#include <skills.h>

typedef struct {
    char *name;
    char *role;
    char *location;
    char *current;
    char *interests[4];
} Engineer;

int main() {
    Engineer me = {
        .name     = "Mithun H N",
        .role     = "Embedded Systems Engineer",
        .location = "Bangalore, India",
        .current  = "Advanced Embedded Systems @ Emertxe (Skill India / NSDC Certified)",
        .interests = {
            "Embedded C & Microcontrollers",
            "IoT & Communication Protocols",
            "Machine Learning on Edge Devices",
            "Low-level System Programming"
        }
    };

    printf("Hello, World! I'm %s\n", me.name);
    printf("I build things that live close to the hardware\n");
    return 0;
}
```

> 🎯 *"To secure a challenging position in Embedded Systems where I can utilize programming, hardware, and problem-solving skills to contribute to organizational growth while continuously enhancing technical knowledge."*

---

## 🛠️ Technical Arsenal

<div align="center">

### 💻 Programming Languages
![C](https://img.shields.io/badge/C-Advanced-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-OOP-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-ML%2FCV-3776AB?style=for-the-badge&logo=python&logoColor=white)

### 🔌 Embedded Platforms & Controllers
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=for-the-badge&logo=raspberry-pi&logoColor=white)
![ESP8266](https://img.shields.io/badge/ESP8266-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)

### 📡 Communication Protocols
![UART](https://img.shields.io/badge/UART-Protocol-blue?style=for-the-badge)
![SPI](https://img.shields.io/badge/SPI-Protocol-blue?style=for-the-badge)
![I2C](https://img.shields.io/badge/I2C-Protocol-blue?style=for-the-badge)
![CAN](https://img.shields.io/badge/CAN-Protocol-blue?style=for-the-badge)

### 🧰 Dev Environment & Tools
![Vim](https://img.shields.io/badge/Vim-019733?style=for-the-badge&logo=vim&logoColor=white)
![GCC](https://img.shields.io/badge/GCC-Compiler-orange?style=for-the-badge&logo=gnu&logoColor=white)
![GDB](https://img.shields.io/badge/GDB-Debugger-red?style=for-the-badge)
![MPLAB](https://img.shields.io/badge/MPLAB-IDE-blue?style=for-the-badge)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white)

</div>

---

## 🚀 Projects Showcase

<details>
<summary>🔍 <strong>Project 1 — Inverted Search Engine</strong> &nbsp;<code>C | Data Structures | Hashing</code></summary>

<br/>

> **"Find any word across thousands of files — instantly."**

Built a high-performance inverted search engine using **hash tables** and **linked lists** to index and retrieve words from multiple text files. Supports database creation, keyword search, save/load operations, and display.

**Key Highlights:**
- ⚡ O(1) average-case lookup using custom hash indexing
- 🧩 Handles duplicate files, empty files, and invalid extensions gracefully
- 🔗 Linked list structure stores per-word frequency + file occurrence data
- 🐛 Solved segfaults through rigorous pointer debugging

**Skills gained:** Hashing, dynamic memory, file validation, modular C programming

</details>

---

<details>
<summary>🔢 <strong>Project 2 — Arbitrary Precision Calculator</strong> &nbsp;<code>C | Doubly Linked Lists | Big Integer Arithmetic</code></summary>

<br/>

> **"Breaking the integer ceiling — one digit at a time."**

Designed an APC capable of performing **+, −, ×, ÷** on numbers of unlimited size, stored digit-by-digit in **doubly linked lists**. Fully command-line driven with carry/borrow logic.

**Key Highlights:**
- 🔢 Handles numbers beyond `long long` limits
- ↕️ Doubly linked list nodes store individual digits for traversal in both directions
- ⚙️ Custom comparison, insertion, and zero-removal helper functions
- 🧠 Step-by-step multiplication/division algorithm design

**Skills gained:** Big integer arithmetic, dynamic memory, algorithm design, CLI processing

</details>

---

<details>
<summary>🎵 <strong>Project 3 — MP3 Tag Reader & Editor</strong> &nbsp;<code>C | File Handling | ID3 Metadata | Bitwise Ops</code></summary>

<br/>

> **"Read, edit, and own your music metadata — from the terminal."**

Built a CLI tool to **view and edit ID3 metadata** (title, artist, album, year) in MP3 files. Uses structures and enums for frame management, with full argument validation and `.mp3` extension checks.

**Key Highlights:**
- 🎼 Parses and edits ID3 frame headers using bit-level operations
- 📁 Validates `.mp3` extension before any file processing
- 🧱 Struct + enum-based design for clean data management
- 🛠️ Supports multiple edit flags in a single command

**Skills gained:** Binary file I/O, bit manipulation, metadata parsing, structured C programming

</details>

---

<details>
<summary>🖼️ <strong>Project 4 — Image Steganography (LSB Encoding)</strong> &nbsp;<code>C | BMP Images | Bit Manipulation | Security</code></summary>

<br/>

> **"Hiding secrets in plain sight — pixel by pixel."**

Implemented an **LSB (Least Significant Bit)** steganography system to hide secret text files inside **BMP images** without perceptible quality loss. Includes both encoder and decoder modules.

**Key Highlights:**
- 🔐 Encodes secret message bit-by-bit into image pixel data
- 🧩 Magic string verification for secure data identification
- 📊 Embeds message size + content into image without visual artifacts
- ↩️ Decoder successfully retrieves original secret text from encoded image

**Skills gained:** Steganography, BMP format parsing, bitwise C programming, security concepts

</details>

---

<details>
<summary>📒 <strong>Project 5 — Address Book Management System</strong> &nbsp;<code>C | File I/O | Structures | CRUD</code></summary>

<br/>

> **"A fully functional contact manager — from scratch in C."**

Developed a **console-based address book** supporting CRUD operations on contacts containing name, phone number, and email. Built with modular programming and persistent file storage.

**Key Highlights:**
- 📋 Full CRUD operations on contact records
- 💾 Persistent storage using file I/O
- 🔍 String-comparison-based search and update logic
- 🧱 Modular, reusable function design

**Skills gained:** File management, struct design, modular programming, string operations

</details>

---

## 🌱 Academic Highlight

### 🤖 Tree-Climbing Robot for Areca Disease Detection & Spraying

> *Final Year B.E. (ECE) Project — VTU*

Built an **autonomous tree-climbing robot** with real-time plant disease detection using **ML + Computer Vision**, enabling targeted pesticide spraying to reduce chemical usage.

| Component | Technology |
|-----------|-----------|
| Vision & ML | TensorFlow · OpenCV · Keras · Pi Camera |
| Controllers | Raspberry Pi · ESP32 |
| Actuation | Servo-based Sprayer · Motor Control |
| IoT | Blynk Software · Sensor Interfacing |

**Impact:** High detection accuracy, minimal chemical waste, supports sustainable agriculture 🌿

---

## 📚 Coursework & Knowledge Base

<div align="center">

| Domain | Topics |
|--------|--------|
| 🖥️ Processor Architecture | Microprocessor · 8086 Instructions · RISC-V 32I Base ISA |
| ⚡ Electronics | Digital Electronics · VLSI |
| 📡 Signal & Image | Digital Signal Processing · Digital Image Processing |

</div>

---

## 🎓 Education

```
📘 B.E. in Electronics & Communication Engineering (ECE)
   Visvesvaraya Technological University (VTU)
   CGPA: 8.13 | 76.13% | 2022–2025

📗 Diploma in ECE
   59.19% | 2018–2021

📙 Class X
   67.20% | 2018
```

---

## 🏅 Certification

> 🇮🇳 **Government of India Certified Program** — Advanced Embedded Systems  
> Emertxe Information Technologies, Bangalore  
> Aligned with **Skill India / NSDC** under **Electronics Sector Skill Council of India (ESSC)**  
> QP Code: **ELE/Q1501 — Embedded Software Engineer**

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=mithunhnnithun2119-ops&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00d4ff&icon_color=00d4ff&text_color=ffffff" height="165"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=mithunhnnithun2119-ops&theme=tokyonight&hide_border=true&background=0d1117&ring=00d4ff&fire=ff6b35&currStreakLabel=00d4ff" height="165"/>

<br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mithunhnnithun2119-ops&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00d4ff&text_color=ffffff&langs_count=6" height="150"/>

</div>

---

## 📬 Let's Connect

<div align="center">

| Platform | Link |
|----------|------|
| 💼 LinkedIn | [linkedin.com/in/mithun-hn](https://www.linkedin.com/in/mithun-hn) |
| 🐙 GitHub | [github.com/mithunhnnithun2119-ops](https://github.com/mithunhnnithun2119-ops/mithunhnnithun2119-ops) |
| 📧 Email | mithunhnmithun2119@gmail.com |
| 📱 Phone | +91 6360192687 |

</div>

---

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,50:1a1a2e,100:0d1117&height=120&section=footer&animation=fadeIn"/>

*"The closer you are to the hardware, the more powerful you become."* ⚡

![Visitor Count](https://komarev.com/ghpvc/?username=mithunhnnithun2119-ops&color=00d4ff&style=for-the-badge&label=PROFILE+VIEWS)

</div>
