<p align="center"><img src="logo.png"><br></p>
<p align="center">
<a href="https://pypi.org/project/qr-filetransfer/"><img src="https://img.shields.io/badge/release-v1.3-blue.svg"></a>
<a href="https://pepy.tech/badge/qr-filetransfe"><img src="https://pepy.tech/badge/qr-filetransfer"></a>
<a href="./LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg"></a>
<a href="https://img.shields.io/badge/support-Linux%20|%20MacOS%20|%20Windows%20-blue.svg"><img src="https://img.shields.io/badge/support-Linux%20|%20MacOS%20|%20Windows%20-blue.svg"></a>
</p>
<p align="center">✨Transfer files over WiFi from your computer to your smartphone from the terminal✨</p>



[![asciicast](https://asciinema.org/a/173861.svg)](https://asciinema.org/a/173861)

## Installation

You will find the most updated version of ```qr-filetransfer``` here. But if you want the most stable version, use ```pip``` to install it

### Pip Install

Global Install

```pip3 install qr-filetransfer```

Local Install

```pip3 install --user qr-filetransfer```

### Git Install

```bash
# clone the repo
$ git clone https://github.com/sdushantha/qr-filetransfer.git

# change the working directory to qr-filetransfer
$ cd qr-filetransfer

# install the requirements
$ pip3 install -r requirements.txt
```


## Usage
```
usage: qr-filetransfer [-h] [-debug] file

Transfer files over WiFi from your computer to your smartphone from the
terminal

positional arguments:
  file             file the you want to transfer

optional arguments:
  -h, --help       show this help message and exit
  -debug, --debug  show the encoded url
```

**Note:** Both devices needs to be connected to the same network

**Exiting**

To exit the program, just press ```CTRL+C```.

---

Transfer a single file
```bash
$ qr-filetransfer /path/to/file.txt
```


Transfer a full directory. **Note:** the directory gets zipped before being transferred
```bash
$ qr-filetransfer /path/to/directory/
```

## Credits
Inspired by the Go project [qr-filetransfer](https://github.com/claudiodangelis/qr-filetransfer)

## License
MIT License

Copyright (c) 2018 Siddharth Dushantha
