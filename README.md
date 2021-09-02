# Qt Desktop Passport Scanner
A desktop passport scanner app built with [Dynamsoft OCR SDK](https://www.dynamsoft.com/label-recognition/overview/), [Qt](https://www.qt.io/) and a USB web camera.

## Trial License
Get a [trial license](https://www.dynamsoft.com/customer/license/trialLicense?product=dlr) to activate passport scanning functions.
 
## Download
- Qt
  - [Windows](https://www.qt.io/download)
  - Linux
    
    ```bash
    sudo apt-get install qt5-default
    ```
    
- [Dynamsoft Label Recognizer 2.0 for Windows and Linux](https://www.dynamsoft.com/barcode-reader/downloads/)

## Build and Run

![Qt desktop passport scanner](https://www.dynamsoft.com/blog/wp-content/uploads/2021/09/passport-scanner-qt-mrz.png)

**Windows**

Add `Qt/5.12.11/mingw73_64/bin` and `Qt/Tools/mingw73_64/bin` to system path.

Run the following commands:

```bash
mkdir build
cd build
cmake -G "MinGW Makefiles" ..
cmake --build .
MRZRecognizer.exe
```

**Linux**

```bash
mkdir build
cd build
cmake ..
cmake --build .
./MRZRecognizer
```
 
