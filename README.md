# hacked_magicCFG
A hacked version of magicCFG which will extract diags bootchain of a device 
## Why is this a 'hacked' version of magicCFG?
* Since the diags bootchains of devices are carefully encoded in magicCFG, this hacked version will extract them if you wish to get the diags bootchain of a device
* Because this hacked version's aim is just to extract the diags bootchain of a device (including iBSS, iBEC (if exists) and diags), it may not boot the device into purple mode properly
## Usage
* Make sure to move magicCFG into `/Applications` first, otherwise bootchain won't be extracted properly
* You're recommended to open magicCFG from `/Applications/MagicCFG.app/Contents/MacOS/MagicCFG` so that you can manage if the process of extracting bootchain
* Steps:
1. Connect a device in DFU mode
2. **Important step**: Open `/Applications/MagicCFG.app/Contents/Frameworks/outdir.txt` file, replace its content with path to the directory where you want the bootchain to be extracted to
3. Open magicCFG, open Diagitizer DBU
4. Hit the icon to start the process and wait for the bootchain of the connected device to be extracted
**NOTE**: The name of bootchain files are randomly generated strings, use an Image4 parser to get their tag
