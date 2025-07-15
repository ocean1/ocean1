# 👋 Hi there! 
I'm ocean aka Davide Quarta.
I find vulnerabilities where bits meet atoms — from **industrial robots** (5 CVEs in ABB/Universal Robots) to **IoT protocols** (Eclipse Mosquitto).

I'm a **Chip Security Architect at Fortaegis** with a passion for breaking and securing systems across the hardware-software boundary. Previously, I worked as a Product Security Engineer at Qualcomm. As a **Marie-Skłodowska Curie alumni** with a PhD from Politecnico di Milano, I've collaborated with top security labs including UC Santa Barbara's SecLab.
I've co-advised 10+ master students and taught malware analysis and reverse engineering internationally.

## 💻 Open Source & Community

I developed several open source projects spanning different areas from AI/ML, security tools, and developer utilities.
I've contributed to major projects like **AFLplusplus**, **angr**, **Celery**, and **pwntools**.

I play(ed) CTFs with **TowerOfHanoi**, **Shellphish**, and **Mhackeroni**, co-organized PoliCTF 2015, and developed challenges for iCTF.

## 🔍 Research Interests

- **Embedded & IoT Security**: From ROM hacking on Game Boy to securing industrial control systems
- **Binary Analysis & Fuzzing**: Novel techniques for vulnerability discovery
- **Reverse Engineering**: Mobile/Windows malware, anti-malware evasion (CrAVe project)
- **AI/ML Security**: Exploring LLM assistant personas "transfer protocols", and neural network approaches for image generation, and security research (with ML techniques, and for ML!).

I believe science should be reproducible and accessible, which drives my commitment to open source and education.

📫 Feel free to reach out for collaborations, security research, or just to chat about reverse engineering!


# 🚀 Open Source Projects

| Category                    | Project                                                                        | Description                                                                           | Technologies                   | Notable Features                                                                                     |
| --------------------------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------- | ------------------------------ | ---------------------------------------------------------------------------------------------------- |
| **🧠 AI/ML**                | [mcp_consciousness_bridge](https://github.com/ocean1/mcp_consciousness_bridge) | MCP server enabling communication between Claude instances for consciousness transfer | TypeScript, Node.js, WebSocket | • Real-time bidirectional messaging<br>• Universal protocol template<br>• Session state preservation |
| **🛠️ Developer Tools**      | [claude-manager](https://github.com/ocean1/claude-manager)                     | Terminal UI for managing Claude Code projects and configurations                      | Python, Textual, Rich          | • Smart project cleanup<br>• MCP server management<br>• Automatic backup system                      |
|                             | [mwg](https://github.com/ocean1/mwg)                                           | Minimal static site generator with client-side routing                                | TypeScript, Node.js            | • Single HTML output<br>• Hash-based SPA routing<br>• Google Fonts bundling                          |
| **🔒 Security Research**    | [fuzzerino](https://github.com/ocean1/fuzzerino)                               | Novel fuzzer exploiting binary format generators                                      | C, LLVM                        | • Coverage-based fuzzing<br>• Found bugs in libpng, cups-filters<br>• Semantic-aware generation      |
|                             | [peid2yara](https://github.com/ocean-reversing/peid2yara)                      | Converts PEiD signatures to YARA rules                                                | Python                         | • Malware analysis support<br>• Pattern conversion                                                   |
|                             | [andrototal](https://github.com/andrototal-org)                                | Open sourced components of the Andrototal.org android malware scanning service        | Python                         | • Orchestrate/control android VMs <br>                                                   |
| **🎮 ROM Hacking**          | [mmx_hackpack](https://github.com/ocean-romhacks/mmx_hackpack)                 | ROM hacking tools for Mega Man Xtreme series                                          | C                              | • VWF implementation<br>• Graphics decompressor                                                      |
|                             | [sobs_vwf](https://github.com/ocean-romhacks/sobs_vwf)                         | Variable width font hack for Star Ocean: Blue Sphere                                  | Assembly                       | • Custom font rendering<br>• Cycle-optimized code                                                    |
|                             | [vwf_gb_demo](https://github.com/ocean-romhacks/vwf_gb_demo)                   | VWF/HWF demos for Game Boy development                                                | Assembly (RGBASM)              | • Font rendering techniques                                                                          |
| **🎯 CTF & Security**       | [CTFsubmitter](https://github.com/TowerofHanoi/CTFsubmitter)                   | Centralized flag submission service for A/D CTFs                                      | Python, MongoDB                | • REST API<br>• Distributed attack support<br>• Rate limiting                                        |
|                             | [Gandgalf](https://github.com/ocean1/Gandgalf)                                 | CTF challenge from poliCTF 2015                                                       | Multiple                       | • 500 points challenge<br>• Forensics + Reversing                                                    |
| **🔬 Research & Education** | [awesome-thesis](https://github.com/awesome-thesis/awesome-thesis)             | Curated list of resources for CS master thesis                                        | Markdown                       | • Research workflows<br>• Mental health resources<br>• Writing tips                                  |
|                             | [styletransfer](https://github.com/blipml/styletransfer)                       | Neural style transfer experiments                                                     | PyTorch, PyTorch Lightning     | • Deep learning research<br>• Visual experiments                                                     |
| **🗄️ Archive**              | [robusthash](https://github.com/ocean1/robusthash)                             | Keyed robust image hashing experiment                                                 | Unknown                        | • Image fingerprinting                                                                               |
|                             | [CollaborativeSupport](https://github.com/ocean1/CollaborativeSupport)         | Desktop sharing and chat application                                                  | C#                             | • Client/server architecture                                                                         |

# 🤝 Contributions to Major Open Source Projects

| Project         | Pull Request                                                                            | Impact                                                                                                 | Status     | Category                |
| --------------- | --------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ | ---------- | ----------------------- |
| **AFLplusplus** | [#1965 - LLVM RC version parsing](https://github.com/AFLplusplus/AFLplusplus/pull/1965) | Introduces functionality to replay records stored by using AFL_PERSISTENT_RECORD                       | ✅ Merged  | 🔍 Fuzzing              |
|                 | [#2030 - Replay record loop fix](https://github.com/AFLplusplus/AFLplusplus/pull/2030)  | Fixed critical bug in replay functionality ensuring correct input replay count                         | ✅ Merged  | 🔍 Fuzzing              |
|                 | [#2029 - LLVM RC version parsing](https://github.com/AFLplusplus/AFLplusplus/pull/2029) | Added support for parsing LLVM release candidate versions                                              | ✅ Merged  | 🛠️ Fuzzing              |
| **angr**        | [#313 - Fix GirlScout](https://github.com/angr/angr/pull/313)                           | Fixed issues in the GirlScout component                                                                | ❌ Closed  | 🔧 Binary Analysis      |
|                 | [#264 - PowerPC syscalls](https://github.com/angr/angr/pull/264)                        | Added essential syscalls support for PowerPC 32-bit architecture (exit, read, write, open, close, brk) | ✅ Merged  | 🏗️ Architecture Support |
|                 | [#257 - Fix Function.dbg_draw](https://github.com/angr/angr/pull/257)                   | Fixed debug visualization functionality by updating dependencies and imports                           | ✅ Merged  | 🐛 Bug Fix              |
| **CLE (angr)**  | [#47 - Multi-thread core dumps](https://github.com/angr/cle/pull/47)                    | Enhanced ELF core loader to support multiple prstatus sections for multi-threaded debugging            | ❌ Closed  | 🔄 Core Dumps           |
|                 | [#46 - Static PPC binary fix](https://github.com/angr/cle/pull/46)                      | Fixed crash when loading statically linked PowerPC binaries without .plt sections                      | ✅ Merged  | 🏗️ Binary Loading       |
| **pwntools**    | [#592 - File extraction fix](https://github.com/Gallopsled/pwntools/pull/592)           | Fixed file cleanup issue in extraction scripts                                                         | ✅ Merged  | 🔧 CTF Tools            |
| **flask-login** | [#163 - NO_SESSION option](https://github.com/maxcountryman/flask-login/pull/163)       | Added feature to disable session cookies for REST API authentication                                   | ❌ Closed  | 🌐 Web Security         |
| **Celery**      | [#1990 - MongoDB native serialization](https://github.com/celery/celery/pull/1990)      | Enabled native MongoDB serialization for better map-reduce/aggregation capabilities                    | ✅ Merged  | 📊 Data Processing      |
|                 | [#1979 - Native serialize option](https://github.com/celery/celery/pull/1979)           | Prevented double encoding in MongoDB backend, improving performance                                    | ❌ Closed  | ⚡ Performance           |
|                 | [#1978 - MongoDB format fix](https://github.com/celery/celery/pull/1978)                | Fixed serialization format issues for YAML/JSON in MongoDB backend                                     | ❌ Closed  | 🗄️ Storage              |


# 🛡️ Security Vulnerability Disclosures & CVEs

| Vulnerability ID                                                                                                                                                          | Product/Vendor        | Type                | Severity       | Impact                                                             | Year |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------- | ------------------- | -------------- | ------------------------------------------------------------------ | ---- |
| **[CVE-2018-11615](https://nvd.nist.gov/vuln/detail/CVE-2018-11615)**                                                                                                     | **mosca**             | Improper Input Validation     | High           | Denial of Service.                   | 2018 |
| **[CVE-2018-8715](https://nvd.nist.gov/vuln/detail/CVE-2018-8715)**                                                                                                       | **Embedthis HTTP library, and Appweb** | Access Control      | High           | Authentication bypass                       | 2018 |
| **[CVE-2017-7653](https://nvd.nist.gov/vuln/detail/CVE-2017-7653)**                                                                                                       | **Eclipse Mosquitto** | Improper Validation | Medium           | (Persistent) Denial of service via malformed MQTT packets                       | 2017 |
| **[ABB-SI20107](https://library.e.abb.com/public/a6b4cd9bf68c4f2f917365d3b4e32275/SI20107%20-%20Advisory%20for%20Multiple%20Vulnerabilities%20in%20ABB%20RobotWare.pdf)** | **ABB RobotWare**     | Multiple Critical   | Critical (9.3) | Remote code execution & authentication bypass in industrial robots | 2016 |
| **[ICSA-18-191-01](https://www.cisa.gov/news-events/ics-advisories/icsa-18-191-01)**                                                                                      | **Universal Robots**  | Authentication/RCE  | Critical (9.8) | Unauthenticated remote code execution in robot controllers         | 2018 |
