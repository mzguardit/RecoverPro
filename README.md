# RecoverPro by MZGuard

**Read-only deleted file recovery, signature carving, and forensic disk acquisition for Windows (10 & 11).**

RecoverPro finds deleted and lost files on **NTFS, FAT12, FAT16, FAT32, and exFAT** drives without touching the source disk. It combines fast file-system analysis with deep signature carving, repairs damaged files where possible, and rates each candidate's recoverability before you save anything.

🌐 **Official Page & Download:** [mzguard.com/recoverpro.html](https://mzguard.com/recoverpro.html)  
🌍 **Languages:** English & Italiano

---

## Core Safety Rules (Enforced by Design)

- **Strict Read-Only Source Access:** Drives and volumes are opened read-only—nothing in the recovery path asks the source disk for write access.
- **SSD & System Drive Warnings:** Flags system volumes and SSDs with TRIM before scanning so you know what to expect.
- **Separate Destination:** Recovered files are always saved to a different drive to prevent overwriting recoverable data.
- **Administrator Only When Needed:** Elevation is requested through the manifest strictly for raw disk access.
- **Authorised Devices Only:** Built for your own drives or media you are legally authorised to examine (enforced with confirmation in Forensic mode).

---

## Screenshots

### Deep Scan & Signature Carving
Recover photos, documents, videos, audio, and archives even when the file system has lost track of them. RecoverPro shows the volume size and clear confirmation limits before starting a deep scan.

![RecoverPro Deep Scan & Carving](https://mzguard.com/recoverpro/deep-scan-carving.png)

### Forensic Acquisition & Verified Imaging
Create verified bit-for-bit volume images with on-the-fly hashing, an audit log, and structured case metadata (case number, examiner, legal authority, and notes).

![RecoverPro Forensic Acquisition](https://mzguard.com/recoverpro/forensic-acquisition.png)

---

## Key Features

### 🔍 Quick Scan & Deep Scan (File Carving)
- **Supported File Systems:** `NTFS`, `FAT12`, `FAT16`, `FAT32`, and `exFAT`.
- **Supported Signatures:** `JPEG`, `PNG`, `GIF`, `BMP`, `TIFF`, `WebP`, `CR2`, `RAW`, `HEIC`, `PDF`, `ZIP & Office (OOXML)`, `SQLite`, `MP4 / MOV`, `MKV`, `MP3`, `WAV`, `FLAC`, `RAR`, `7z`, `AVI`, `AIFF`, `CAB`, `ICNS`.

### 📊 Recoverability Ratings & File Repair
- Every discovered file carries a recoverability rating (**Excellent**, **Good**, **Partial**, or **Poor**) along with the reason behind it.
- Results stay labelled as **provisional** until their contents are verified—so you never mistake a directory entry for a healthy file.
- **Repair Pass:** Damaged files go through an automatic repair pass where possible.
- **Search & Filter:** Search by name or path and filter by file type, size, and date.

### 🛡️ Forensic Disk Imaging
- Bit-for-bit volume imaging with **hash calculation during write**, audit logs, and exportable reports.
- Never overwrites an existing image or destination file.

---

## Editions & Requirements
- **OS:** Windows 10 or Windows 11 (Administrator privileges required for raw disk reads).
- **Free Start:** Includes **100 free file recoveries**; a paid licence removes the recovery limit.

---

## Part of the MZGuard Suite
Developed by **Vincenzo Chieppa** / [MZGuard](https://mzguard.com/) · [github.com/mzguardit](https://github.com/mzguardit)
