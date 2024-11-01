# File Hashes

This document provides the MD5 hashes for the files included in the **challenges** directory. These hashes can be used to verify the integrity of the files.

| **File Path**                        | **MD5 Hash**                      |
|--------------------------------------|-----------------------------------|
| `in_plain_sight/in_plain_sight.exe`  | DDAB0E61485AC6C86835861DB972FC08  |
| `gocrackme3/GoCrackMe3.zip`          | 39D58192BFE511BAB7E0A2740B6F3A0A  |
| `thats_life/gameoflife`              | 1EE999E3F6C2B0BCCD0C7D9DE2E2C9BA  |
| `oceanlocust/ocean_locust.7z`         | 2A44CE882235FF9A15006A554FC4B83C  |
| `rusty_bin/rusty_bin.exe`            | 5DAF721C41A7AE54656A1208338994CE  |

## How to Verify File Hashes

You can verify the MD5 hash of a file using PowerShell with the following command:

```powershell
Get-FileHash .\path\to\your\file -Algorithm MD5
