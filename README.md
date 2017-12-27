## helga-build

Notes on workstation/miningstation built in December 2017.

-----------------------------------------------------

### Hardware Specs

+ **Case.** Thermaltake Core P3 SE Snow Ed. ATX Open Frame Tt LCS Certified Case (CA-1G4-00M6WN-02) ($109.99).
+ **Power Supply.** Corsair RMx Series RM850x 850W 80+ Gold Certified Fully Modular (CP-9020156-NA) ($159.99).
+ **Motherboard.** [ASUS PRIME Z370-A](https://www.asus.com/us/Motherboards/PRIME-Z370-A/HelpDesk_Manual/) LGA1151 DDR4 DP HDMI DVI M.2 USB 3.1 Z370 ATX for 8th Gen Intel Core Processors ($174.99).
+ **CPU.** [Intel 8th Gen Core i7-8700 Processor](https://www.intel.com/content/www/us/en/products/processors/core/i7-processors/i7-8700.html) TPD: 65W (BX80684I78700) ($339.99).
+ **GPU 0.** [MSI Radeon RX 570](https://www.msi.com/Graphics-card/Radeon-RX-570-GAMING-X-8G.html) DirectX 12 8GB 256-Bit GDDR5 PCI Express x16 HDCP CrossFireX ATX Video Card ($249.99).
+ **GPU 1.** [ASUS Geforce GTX 1050 O2GB Dual-Fan Edition](https://www.asus.com/us/Graphics-Cards/DUAL-GTX1050-2G/) DVI-D HDMI DP 1.4 (DUAL-GTX1050-O2G) ($127.99).  
+ **GPU 2.** [ASUS Geforce GTX 1050 O2GB Dual-Fan Edition](https://www.asus.com/us/Graphics-Cards/DUAL-GTX1050-2G/) DVI-D HDMI DP 1.4 (DUAL-GTX1050-O2G) ($127.99).  

+ **RAM.** Ballistix Sport LT 16GB Kit (8GBx2) DDR4 2666 MT/s (PC4-21300) SR x8 DIMM 288-Pin ($173.99).  
+ **SSD.** Samsung 960 EVO Series - 250GB PCIe NVMe - M.2 Internal SSD (MZ-V6E250BW) ($127.99).  
+ **WiFi.** Panda N600 Dual Band (2.4GHz, 5.0GHz) 300Mbps Wireless N USB Adapter ($19.99).  
+ **Cooling.**
  - 1 x Cooler Master Sleeve Bearing 120mm Silent Fan (4 for $12.55).
  - 2 x AigoDIY, Halo LED 120mm Cooling Neon Quite Clear Fan Mod 4 Pin/3 Pin ($17.99).  
  - Enermax ETS-T40 CPU Cooler, 4xhigh-perf 6mm heat pipes, 200W, 140mm PWM Fan (ETS-T40F-RF) ($35.48).  

**Approx. Total Cost:** $110 + 160 + 175 + 340 + 250 + 128 + 128 + 174 + 128 + 20 + 12 + 18 + 35 = $1,678.

-------------------------------------------------------

### Detailed Specs of Primary Components

+ **CPU.** Intel 8th Gen Core i7-8700 Processor.   
  - Compatible only with Motherboards based on Intel 300 Series Chipsets
  - 6 Cores/12 Threads
  - 3.20 GHz up to 4.60 GHz Max Turbo Frequency
  - 12 MB Smart Cache
  - Intel Optane Memory Supported
  - Intel UHD Graphics 630socket h4
  - **Advertised Power Draw:	65W**

+ **GPU 0.** [MSI Radeon RX 570](https://www.msi.com/Graphics-card/Radeon-RX-570-GAMING-X-8G.html)
  - 8GB 256-Bit GDDR5
  - Core Clock
    * 1293 MHz (OC Mode)
    * 1281 MHz (Gaming Mode)
    * 1244 MHz (Silent Mode)
  - 1 x DL-DVI-D 2 x HDMI 2 x DisplayPort
  - 2048 Stream Processors
  - PCI Express x16

+ **GPU 1 & 2.** ASUS Geforce GTX 1050 O2GB Dual-Fan Edition DVI-D HDMI DP 1.4.   
  - New NVIDIA Pascal™ architecture delivers improved performance and power efficiency.
  - Classic and modern games at 1080p @ 60 FPS
  - Supports the latest DirectX™ 12 and GeForce gaming features
  - Dual-fan Cooling provides double the airflow with 3x quieter performance
  - Auto-Extreme Technology with aerospace-grade Super Alloy Power II components
  - GPU Tweak II performance and streaming monitoring
  - **Advertised Power Draw: 75W**

+ **Motherboard.** ASUS PRIME Z370-A LGA1151 DDR4 DP HDMI DVI M.2 USB 3.1 Z370 ATX for 8th Gen Intel Core Processors.
  - Designed exclusively for 8th generation Intel Core processors to maximize connectivity and speed with Dual M.2, USB 3.1 Gen2, Intel Thunderbolt 3 support and Intel Optane Memory compatibility
  - 5-Way Optimization with Auto-Tuning and FanXpert 4 automatically tailors overclocking profiles to your unique build for maximum OC performance and dynamic system cooling
  - Unmatched Personalization with ASUS exclusive AURA Sync RGB lighting, additional RGB header and 3D-printing mounts
  - Two Patent-pending Safe Slots feature an injection molding process that integrates metal framing for a stronger, firmly anchored PCIe slot built for heavyweight GPUs
  - Industry-leading 8-channel HD audio enhanced by ASUS exclusive Realtek S1220A featuring Crystal Sound 3 and driven by Japanese capacitors for warm, immersive sound

------------------------------------------------------------

### Software
+ **OS.** Ubuntu 17.04
+ **Mining.** Can't mine Ethereum with 2Gb cards anymore.  Mining ZCash is still possible, however.
  - **ZCash.**
    * https://github.com/zcash/zcash/wiki/Debian-binary-packages
    * https://github.com/zcash/zcash/wiki/Mining-Guide
    * https://www.cryptocompare.com/mining/guides/how-to-mine-zcash-with-cpu-linux/
    * https://forum.z.cash/t/tips-for-nvidia-linux-miners/21868
  - **Ethereum.**
    * https://www.meebey.net/posts/ethereum_gpu_mining_on_linux_howto/
