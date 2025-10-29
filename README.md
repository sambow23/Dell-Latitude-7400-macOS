# Dell Latitude 7400
<img src="https://github.com/user-attachments/assets/e283ae05-9c5e-48fa-97f3-34ded531bb59" alt="drawing" width="500"/>


| Hardware  | |
| ------------- | ------------- |
| CPU  | Intel® Core™ i5-8365U |
| RAM  | 32GB DDR4 |
| GPU  | Intel UHD Graphics 620  |
| Network  | Intel® Wi-Fi AC 9560 |
| Storage  | Western Digital® PC SN520 512GB |
| OS  | macOS Ventura 13.7.6 |
| Screen  | 14" 1920x1080 |
| Bootloader | OpenCore 1.0.5 | 

## Hardware compatibility

#### What works
- CPU power management
- GPU acceleration and video codecs
- SSD (NVME)
- Wi-Fi (AirportItlwm.kext)
- All USB ports (mapped)
- USB-C Video
- Trackpad
- FN Keys
- Webcam
- Screen Brightness
- Internal Audio (Speakers, Microphone)
- Battery percentage
- Sleep
- Thunderbolt (no hotplug yet)

#### Untested
- iCloud Services
- Bluetooth (no kext installed \ disabled in BIOS)
- SD Card Reader (disabled in BIOS)

#### Notes
* Battery life is horrible due to the Thunderbolt controller being constantly on, even when disabled in the BIOS...

#### Not working
- You tell me
