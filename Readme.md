# Flash Guide
Xiaomi Pad 6 Build releases

<h2>Installation Guide</h1>
<div>
<h3>NOTE: Make sure to use HyperOS Global or China based on Android 14 Firmware, don't try to run this ROM with Miui Firmware</h2>
  <ol>
    <li>Download the rom package along with boot,dtbo and vendor_boot(links mentioned in post)</li>
    <li>Put downloaded files in a folder(your platform tools folder preferred)</li>
    <li>reboot to bootloader(hold power + volume down button)</li>
    <li>In your pc,open terminal where you copied the above files and run the following commands:</li>
<br>
    
    fastboot flash boot boot.img
<br>

    fastboot flash dtbo dtbo.img
<br>
    
    fastboot flash vendor_boot vendor_boot.img
 <br>
 
    fastboot reboot recovery
<br>
    <li>Format data via recovery(optional if flashing on the same rom)</li>
    <li>select reboot to recovery(advanced -> reboot to recovery)</li>
    <li>select apply update in recovery</li>
    <li>In your pc terminal, run adb sideload rom.zip(replace rom.zip with the downloaded rom package name.zip)</li>

  # If you are flashing vanilla build and want gapps
  
<li>Google Apps for A14:  <a href="https://github.com/MindTheGapps/14.0.0-arm64/releases">Here</a></li>
<li>Google Apps for A15:  <a href="https://github.com/MindTheGapps/15.0.0-arm64/releases">Here</a></li>
<li>Magisk:  <a href="https://github.com/topjohnwu/magisk/releases">Here</a></li>
<li>We recommend MinMicroG installed before the first boot,<br>either Minimal or MinimalPhonesky variant<br>
microG Installer:  <a href="https://github.com/FriendlyNeighborhoodShane/MinMicroG-abuse-CI/releases">Here</a></li>

<div>
</div>
<br>
