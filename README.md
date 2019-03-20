# UEF-Extractor
Small windows app to extract raw UEF files from compressed UEF so they can be played on TZXDuino.
If you want to play UEF files into your Acorn Electron or BBC Micro through a TZXduino the raw UEF files have to be extracted from the UEF Files.
By default UEF are compressed using Gzip. Due to small usable memory on an Arduino Nano its near impossible to have TZXduino unzip the files first.
So for TZXduino to play the UEF they have to be in raw format which means decompressing them first.
I made this tool to help decompress the files in bulk becuase its a 2 step process.
My tool automates the 2 step process.
