# wiringOP README

This is a modified WiringPi for OrangePi PC2.
Tested on Orangepi PC2 H5

## Download
### For Orangepi Pi PC2 H5
    git clone https://github.com/tomiisp/WiringOP.git -b h5
## Installation
    cd WiringOP
    chmod +x ./build
    sudo ./build

```    
orangepi@orangepi:~$ gpio readall
 +-----+-----+-----------+------+---+-Orange Pi+---+------+-----------+-----+-----+
 | BCM | wPi |   Name    | Mode | V | Physical | V | Mode | Name      | wPi | BCM |
 +-----+-----+-----------+------+---+----++----+---+------+-----------+-----+-----+
 |     |     |      3.3v |      |   |  1 || 2  |   |      | 5v        |     |     |
 |  12 |   8 |     SDA.0 | ALT5 | 0 |  3 || 4  |   |      | 5V        |     |     |
 |  11 |   9 |     SCL.0 | ALT5 | 0 |  5 || 6  |   |      | GND       |     |     |
 |   6 |   7 |    GPIO.7 | ALT3 | 0 |  7 || 8  | 0 | OUT  | GPIO.15   | 15  | 69  |
 |     |     |       GND |      |   |  9 || 10 | 0 | OUT  | GPIO.16   | 16  | 70  |
 |   1 |   0 |      RxD2 | ALT5 | 0 | 11 || 12 | 1 | OUT  | GPIO.1    | 1   | 110 |
 |   0 |   2 |      TxD2 | ALT5 | 0 | 13 || 14 |   |      | GND       |     |     |
 |   3 |   3 |      CTS2 | ALT3 | 0 | 15 || 16 | 1 | OUT  | GPIO.4    | 4   | 68  |
 |     |     |      3.3v |      |   | 17 || 18 | 1 | OUT  | GPIO.5    | 5   | 71  |
 |  15 |  12 | MOSI/RTS3 | ALT3 | 0 | 19 || 20 |   |      | GND       |     |     |
 |  16 |  13 | MISO/CTS3 | ALT3 | 0 | 21 || 22 | 0 | ALT3 | RTS2      | 6   | 2   |
 |  14 |  14 |  SCK/TxD3 | ALT4 | 0 | 23 || 24 | 0 | ALT4 | CS/RxD3   | 10  | 13  |
 |     |     |       GND |      |   | 25 || 26 | 1 | OUT  | GPIO.11   | 11  | 21  |
 |  19 |  30 |     SDA.1 | ALT3 | 0 | 27 || 28 | 0 | ALT3 | SCL.1     | 31  | 18  |
 |   7 |  21 |   GPIO.21 | ALT2 | 0 | 29 || 30 |   |      | GND       |     |     |
 |   8 |  22 |   GPIO.22 |  OUT | 1 | 31 || 32 | 0 | ALT3 | RTS1      | 26  | 200 |
 |   9 |  23 |   GPIO.23 |  OUT | 1 | 33 || 34 |   |      | GND       |     |     |
 |  10 |  24 |   GPIO.24 | ALT3 | 0 | 35 || 36 | 0 | ALT3 | CTS1      | 27  | 201 |
 | 107 |  25 |   GPIO.25 | ALT3 | 0 | 37 || 38 | 0 | ALT5 | TxD1      | 28  | 198 |
 |     |     |       GND |      |   | 39 || 40 | 0 | ALT5 | RxD1      | 29  | 199 |
 +-----+-----+-----------+------+---+----++----+---+------+-----------+-----+-----+
 | BCM | wPi |   Name    | Mode | V | Physical | V | Mode | Name      | wPi | BCM |
 +-----+-----+-----------+------+---+-Orange Pi+---+------+-----------+-----+-----+


