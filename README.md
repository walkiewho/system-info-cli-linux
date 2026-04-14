# system-info-cli-linux
printing information about your hardware, os, etc.

---
# Informations type
### You can recive information about:
#### System
- Hostname
- Kernel
- Kernel version
- Architecture
- OS
- OS Version
- OS ID like
- Uptime
- Load average
- Users logged
- Last boot
- Default shella
- Terminal
- Desktop
- Session

#### Cpu
- Model name
- Cores number
- Frequency
- Min/Max frequency
- Governor
- Temperature
  
#### Gpu
- Model
- Vendor
- Bus
- Subsysten
- Driver
- Revisions

#### Vulkan
- API version
- Driver
- Device

#### Opengl
- Version
- Renderer
- Vendor
- GLSL
- Extensions count
- Hardware accel

#### Battery
- Capacity
- Status
- Treshold
- Cycles count
- Battery health
- Power
- Time to empty/full
- Technology

#### Ram
- Used/Total RAM
- Used/Total swap
- RAM free
- Swap free
- Cached memory

#### Disk
- Model
- Size
- Type
- Partitions count
- Root used / size
- Root available

#### Mounts
- Every unique mount point used / total

#### Net
- MAC
- Wi-Fi:
  - SSID
  - Signal
  - Bitrate
  - Frequency band
- Ethernet
  - Speed
- Status

#### Bluetooth
- Adapter
- MAC
- Status
- Powered
- Paired devices


---
# dependency commands
## Necessarily
bash
hostname, uname, who
bc
cat, grep, awk, sed, echo, printf, basename, xargs, head, tail, wc, cut
dfa
ip, iw
bluetoothctl
lspci, vulkaninfo, glxinfo

## Optional
Battery (for laptops): upower

---

