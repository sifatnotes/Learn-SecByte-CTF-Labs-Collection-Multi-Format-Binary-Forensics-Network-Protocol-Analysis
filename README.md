# Learn-SecByte-CTF-Labs-Collection-Multi-Format-Binary-Forensics-Network-Protocol-Analysis
A curated collection of hands-on cybersecurity CTF labs covering PE/ELF/Mach-O Binary Forensics, Static Analysis Fundamentals, Network Protocol Reconnaissance (TCP/IP), Windows Registry, File System Mechanics, and Memory Management from Learn SecByte.
# Learn SecByte CTF & Cybersecurity Labs Collection

Welcome to the **Learn SecByte CTF & Cybersecurity Labs Collection**. This repository is a dedicated, searchable index of hands-on static malware analysis, cross-platform binary forensics (PE, ELF, Mach-O), network protocol investigation, and operating system internal mechanics labs designed for cybersecurity students, CTF players, malware analysts, SOC engineers, and digital forensics professionals.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Building foundational expertise across multi-platform binary structures, lower-level operating system subsystems, and network transport protocols is essential for comprehensive security analysis. Hosted on [Learn SecByte](https://learn.secbyte.org/), this collection of CTF challenge labs provides practical training across core analysis domains.

From extracting obfuscated strings and computing cryptographic file hashes, to auditing Windows Portable Executable (PE), Linux Executable and Linkable Format (ELF), and macOS Mach-O binary headers, analyzing TCP/IP communication protocols, and inspecting Windows Registry hives, file system artifacts, and virtual memory management structures, these exercises develop well-rounded technical investigation skills.

---

## Lab Collection & Index

Below is the complete, searchable index of all binary forensics, network analysis, and OS internals challenges in this collection:

| # | Lab / Challenge Name | Category | Focus / Key Topics | Lab Link |
|---|----------------------|----------|---------------------|----------|
| 1 | **Strings Sleuth: Hidden Text in Binaries** | Static Foundations | ASCII/Unicode string extraction, FLOSS/strings usage, stack string decoding | [Access Lab](https://learn.secbyte.org/ctf/strings-sleuth-hidden-text-in-binaries) |
| 2 | **Hashing and File Identification Lab** | Static Foundations | Cryptographic hashes (MD5/SHA256), ssdeep fuzzy hashing, VirusTotal/VT API queries | [Access Lab](https://learn.secbyte.org/ctf/hashing-and-file-identification-lab) |
| 3 | **Static Malware Analysis Fundamentals 2** | Static Foundations | Triage methodology, file signature/magic byte verification, initial risk scoring | [Access Lab](https://learn.secbyte.org/ctf/static-malware-analysis-fundamentals-2) |
| 4 | **Mach-O Binary Forensics: Inside the macOS Executable Format** | Multi-Platform Binaries | Mach-O load commands, fat binaries/universal architectures, segment/section layout | [Access Lab](https://learn.secbyte.org/ctf/macho-binary-forensics-inside-the-macos-executable-format) |
| 5 | **ELF Anatomy: Header to Hardened Binary** | Multi-Platform Binaries | ELF header parsing, program/section headers, dynamic linking, security hardening (PIE/RELRO) | [Access Lab](https://learn.secbyte.org/ctf/elf-anatomy-header-to-hardened-binary) |
| 6 | **Portable Executable Forensics Lab** | Multi-Platform Binaries | PE structure, Data Directories, import/export tables, resource section forensics | [Access Lab](https://learn.secbyte.org/ctf/portable-executable-forensics-lab) |
| 7 | **Common Malware Communication Protocols** | Network Protocol Analysis | HTTP/S, DNS, C2 communication channels, protocol header anomalies, beaconing | [Access Lab](https://learn.secbyte.org/ctf/common-malware-communication-protocols) |
| 8 | **TCP/IP for Malware Analysis: Packet Trail Recon** | Network Protocol Analysis | TCP handshakes, window size anomalies, IP flags, raw packet stream parsing | [Access Lab](https://learn.secbyte.org/ctf/tcp-ip-for-malware-analysis-packet-trail-recon) |
| 9 | **Network Sleuthing for Malware Analysts** | Network Protocol Analysis | Packet capture triage, PCAP flow filtering, malicious traffic correlation | [Access Lab](https://learn.secbyte.org/ctf/network-sleuthing-for-malware-analysts) |
| 10 | **Windows Registry Fundamentals** | Operating System Internals | Registry hives (HKLM/HKCU), SAM/SYSTEM/SOFTWARE parsing, autostart keys | [Access Lab](https://learn.secbyte.org/ctf/windows-registry-fundamentals) |
| 11 | **Filesystem Forensics Under the Hood** | Operating System Internals | NTFS MFT parsing, FAT directory entries, EXT4 inode structures, file slack analysis | [Access Lab](https://learn.secbyte.org/ctf/filesystem-forensics-under-the-hood) |
| 12 | **Memory Management Fundamentals** | Operating System Internals | Virtual vs. physical memory, paging, page tables, memory protection flags (`PAGE_EXECUTE_READWRITE`) | [Access Lab](https://learn.secbyte.org/ctf/memory-management-fundamentals) |

---

## Categories

### 1. Static Analysis Foundations & Triage
Master initial file identification, string extraction, cryptographic hashing, and signature verification techniques.
- [Strings Sleuth: Hidden Text in Binaries](https://learn.secbyte.org/ctf/strings-sleuth-hidden-text-in-binaries)
- [Hashing and File Identification Lab](https://learn.secbyte.org/ctf/hashing-and-file-identification-lab)
- [Static Malware Analysis Fundamentals 2](https://learn.secbyte.org/ctf/static-malware-analysis-fundamentals-2)

### 2. Multi-Platform Binary Structure Forensics
Deconstruct executable binary formats across Windows, Linux, and macOS platforms to locate suspicious headers and sections.
- [Portable Executable Forensics Lab](https://learn.secbyte.org/ctf/portable-executable-forensics-lab)
- [ELF Anatomy: Header to Hardened Binary](https://learn.secbyte.org/ctf/elf-anatomy-header-to-hardened-binary)
- [Mach-O Binary Forensics: Inside the macOS Executable Format](https://learn.secbyte.org/ctf/macho-binary-forensics-inside-the-macos-executable-format)

### 3. Network Protocols & Packet Analysis
Investigate low-level network packet captures, analyze transport layer flags, and profile malicious C2 traffic.
- [TCP/IP for Malware Analysis: Packet Trail Recon](https://learn.secbyte.org/ctf/tcp-ip-for-malware-analysis-packet-trail-recon)
- [Common Malware Communication Protocols](https://learn.secbyte.org/ctf/common-malware-communication-protocols)
- [Network Sleuthing for Malware Analysts](https://learn.secbyte.org/ctf/network-sleuthing-for-malware-analysts)

### 4. Operating System & Subsystem Internals
Examine underlying system architectures including registry stores, file system structures, and memory pagination.
- [Windows Registry Fundamentals](https://learn.secbyte.org/ctf/windows-registry-fundamentals)
- [Filesystem Forensics Under the Hood](https://learn.secbyte.org/ctf/filesystem-forensics-under-the-hood)
- [Memory Management Fundamentals](https://learn.secbyte.org/ctf/memory-management-fundamentals)

---

## Learning Path

Follow this structured learning pathway to establish robust fundamentals in binary forensics, network analysis, and system internals:

1. **Phase 1: Static Triage & Identification** — Learn basic file extraction, hashing, and string auditing:
   - [Hashing and File Identification Lab](https://learn.secbyte.org/ctf/hashing-and-file-identification-lab)
   - [Strings Sleuth: Hidden Text in Binaries](https://learn.secbyte.org/ctf/strings-sleuth-hidden-text-in-binaries)
   - [Static Malware Analysis Fundamentals 2](https://learn.secbyte.org/ctf/static-malware-analysis-fundamentals-2)

2. **Phase 2: Multi-Platform Binary Forensics** — Analyze execution formats across Windows, Linux, and macOS:
   - [Portable Executable Forensics Lab](https://learn.secbyte.org/ctf/portable-executable-forensics-lab)
   - [ELF Anatomy: Header to Hardened Binary](https://learn.secbyte.org/ctf/elf-anatomy-header-to-hardened-binary)
   - [Mach-O Binary Forensics: Inside the macOS Executable Format](https://learn.secbyte.org/ctf/macho-binary-forensics-inside-the-macos-executable-format)

3. **Phase 3: Network Reconnaissance & Protocol Inspection** — Trace packet flows and C2 communication channels:
   - [TCP/IP for Malware Analysis: Packet Trail Recon](https://learn.secbyte.org/ctf/tcp-ip-for-malware-analysis-packet-trail-recon)
   - [Common Malware Communication Protocols](https://learn.secbyte.org/ctf/common-malware-communication-protocols)
   - [Network Sleuthing for Malware Analysts](https://learn.secbyte.org/ctf/network-sleuthing-for-malware-analysts)

4. **Phase 4: OS Internals & Subsystem Forensics** — Audit core system structures, storage, and memory models:
   - [Windows Registry Fundamentals](https://learn.secbyte.org/ctf/windows-registry-fundamentals)
   - [Filesystem Forensics Under the Hood](https://learn.secbyte.org/ctf/filesystem-forensics-under-the-hood)
   - [Memory Management Fundamentals](https://learn.secbyte.org/ctf/memory-management-fundamentals)

---

## How to Use the Labs

1. Select a challenge link from the index or category sections above.
2. Read the scenario directives and target files provided on [Learn SecByte](https://learn.secbyte.org/).
3. Use file inspection tools (PEStudio, `readelf`, `otool`, `strings`, `ssdeep`), packet analyzers (Wireshark, TShark), and forensic utilities (Registry Explorer, FTK Imager) inside a dedicated sandbox VM.
4. Extract hidden strings, inspect header boundaries, analyze network packets, parse system artifacts, and retrieve target flags.

---

## Disclaimer

This repository and its linked resources are strictly intended for educational, threat research, and authorized technical training purposes. Never analyze untrusted binaries or packet captures outside an isolated laboratory environment.
