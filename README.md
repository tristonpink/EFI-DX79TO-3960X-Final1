# EFI-DX79TO-3960X-Final1
Successful with SMBIOS MacPro6.1, but hardware decoding of RX480 is not working. MacOS:Mojave 10.14.5.
I have to change the SMBIOS to iMacPro1.1, now I am working with it , but got stuck at USB.

EmuVariableUEFI.EFI and boot args:npci=0x3000,slide=0 is necessary , and audio injecting 99 with AppleALC.kext works well .

Hardware list :
CPU:I7 3960X 
MB：Intel DX79TO 
Memory：ADATA DDR3 1600 OC 2133MHz 
Harddisk：WD SATA 512G 
PCIe#1:Saphire RX480 8G 
PCIe#2:null 
PCIe#3:null 
PCIe#4:Broadcom BCM4360 802.11ac Wireless Network Adapter 
PCIe#5:VIA USB 3.0 eXtensible Host Controller

SATA Controller：Intel(R) C600 series chipset SATA AHCI Controller（onboard） 
Audio：Realtek ALC892（onboard） 
Network：Intel(R) 82579LM Gigabit Ethernet Device(onboard)
