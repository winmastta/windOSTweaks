# windOSTweaks

> The core optimization logic and scripts behind **windOS**.

![Banner](https://capsule-render.vercel.app/api?type=waving&color=0078D4&height=200&section=header&text=windOSTweaks&fontSize=80&animation=fadeIn&fontAlignY=35&desc=Registry.%20PowerShell.%20Debloat.&descAlignY=55&descSize=20)

### 📋 Overview

This repository contains the raw registry modifications, PowerShell scripts, and batch files used to transform a stock Windows installation into **windOS**. These tweaks focus on reducing latency, removing telemetry, and optimizing system resource usage.

- **Parent Project:** [windOS](https://windos.nn1kk00.ru/)
- **Target OS:** Windows 10 LTSC / Windows 11
- **License:** Open Source

### ⚙️ What's Inside?

| Component | Description |
| :--- | :--- |
| **Registry Hacks** | Modifications for menu speed, gaming priority, and visual effects. |
| **Service Configs** | Disabling SysMain, DiagTrack, WSearch, and other non-essential services. |
| **Debloat Scripts** | Removal of UWP apps, Cortana, OneDrive, and Edge integration. |
| **Privacy Tools** | Blocking telemetry hosts and disabling advertising IDs. |

### 🚀 Usage

You can run these scripts individually on an existing system or integrate them into an ISO.

```powershell
# Example: Run the main debloat script
Set-ExecutionPolicy Unrestricted -Scope Process
.\scripts\main_debloat.ps1
```

### ⚠️ Warning

These scripts make deep changes to the Windows Registry and System Files.
*   Always create a Restore Point before applying.
*   Some Windows features (Store, Xbox Game Bar) may be disabled depending on the script used.

### 🏆 Credits

**Maintained by:**
*   [winmastt](https://github.com/winmastt)
*   [nn1kk00](https://github.com/nn1kk00)

---
*Visit the main website: [windos.nn1kk00.ru](https://windos.nn1kk00.ru/)*
