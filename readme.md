# 變色龍 ChameleonMini

<https://cdn.statically.io/gh/emsec/ChameleonMini/master/Doc/Doxygen/html/Page_GettingStarted.html>

## Windows

### 安裝驅動 Atmel USB DFU Programmer

<https://sourceforge.net/projects/dfu-programmer/>

進到 `DFU Flash Firmware` 資料夾中，安裝符合作業系統的驅動。

### 安裝 ChameleonDriver

進到 `ChameleonDriver` 資料夾中，對 `ChameleonDriver.inf` 按右鍵，點選「安裝」。

### 上傳驅動

先讓裝置進入 DFU 模式 (在裝置關機狀態下，按住 USB 旁的黃色按鈕，然後在接上 USB，如果是 Tiny 請按下 B 鍵)，然後進到 `dfu` 資料夾中，請先確保要燒錄的 `Chameleon-Mini.eep` 和 `Chameleon-Mini.hex` 放在與 `ChameleonFirmwareUpgrade.bat` 同一個目錄下，然後對 `ChameleonFirmwareUpgrade.bat` 按右鍵，以系統管理員身份執行。

最新的韌體可能可以在以下的網址找到：

* <https://github.com/emsec/ChameleonMini/tree/master/Firmware/Chameleon-Mini/Latest>
* <https://github.com/RfidResearchGroup/ChameleonMini/tree/proxgrind/Firmware/Chameleon-Mini/Latest>