# Micronova processor module for Ghidra

## Installing

- Download the zip file from the dist directory.
- Start Ghidra
- Menu File -> Install extensions
- Click the "+" icon, select the downloaded zip file, OK

## Using the extension
- File -> Import file, select a Micronova binary file
- Set options: 
    - Format: Raw binary
	- Language: Micronova default
	- Press Options button, set the address at which the file should be loaded
	
## Note:
In the extension, each address corresponds to a 16-bit word. However, when importing a file, the loading address in 
the "options" dialog is in bytes. In other words, if you want the file loaded at word-address 0100 (0x40), you need to set base address 0x80.

## Building the extension
Coming soon..

