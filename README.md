# GIGABYTE-GA-H270M-DS3H

OpenCore EFI for Gigabyte GA-H270M-DS3H

![about](https://raw.githubusercontent.com/randvmbone/GIGABYTE-H270M-DS3H/main/about.png)

### Hardware

* **MOBO:** Gigabyte GA-H270M-DS3H
* **CPU:** Intel Core i5-7400
* **RAM:** Mushkin DDR4-2400 16GB (2x8GB)
* **GPU:** AMD Radeon RX Vega 64
* **SSD:** Patriot Burst 240GB

### BIOS Settings

* Settings
	* BIOS
	  * Fast Boot → **Disabled**
	  * Windows 8/10 Features → **Windows 8/10**
	  * CSM Support → **Disabled**
	* Peripherals
	  * Initial Display Output → **PCIe 1 Slot**
	  * Intel Platform Trust Technology (PTT) → **Enabled**
	  * Super IO Configuration
	    * Serial Port → **Disabled**
	    * Parallel Port → **Disabled**
	  * USB Configuration
	    * Legacy USB Support → **Enabled**
	    * XHCI Hand-off → **Enabled**
	* Chipset
	  * VT-d → **Disabled**
	  * Internal Graphics → **Disabled**

### macOS Support
| Version   | macOS | Download |
| --------: | :---- | :------- |
| 14.2 | Sonoma | [Mac App Store](https://apps.apple.com/app/macos-sonoma/id6450717509?mt=12) |
| 13.6 | Ventura | [Mac App Store](https://apps.apple.com/app/macos-ventura/id1638787999?mt=12) |
| 12.7 | Monterey | [Mac App Store](https://apps.apple.com/app/macos-monterey/id1576738294?mt=12) |
| 11.7.10 | Big Sur | [Mac App Store](https://apps.apple.com/app/macos-big-sur/id1526878132?mt=12) |
| 10.15.7 | Catalina | [Mac App Store](https://apps.apple.com/app/macos-catalina/id1466841314?mt=12) |
| 10.14.6 | Mojave | [Mac App Store](https://apps.apple.com/app/macos-mojave/id1398502828?mt=12) |
| 10.13.6 | High Sierra | [Mac App Store](https://apps.apple.com/app/macos-high-sierra/id1246284741?mt=12) |

### Sonoma
* OCLP
	* ```boot-args: amfi=0x80 ipc_control_port_options=0```
