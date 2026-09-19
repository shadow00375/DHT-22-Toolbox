# DHT-22-Toolbox

> The package includes an arduino assembly for measuring the ambient temperature and humidity via a DHT-22 sensor and a reader to record the mass from a balance from a USB Type-B port.<br>
> These are some simple programs I made for data collection during my last research project.<br>
> Just trying to put stuffs up here and just in case if anyone needs these ;)

## Software & Dependencies

### Arduino Environment

The `Humidity_sensor.ino` sketch was built using the Arduino IDE with the following libraries:

- **Adafruit Unified Sensor** (v1.1.15)
- **DHT sensor library** by Adafruit (v1.4.7)

### Python Environment

The `DHT-22 Data logger.py` script requires the following Python package:

- **PySerial** (v3.5 was used for development)

## Usage

1.  **Upload the Arduino Sketch:**
    Open `Humidity_sensor.ino` in the Arduino IDE and upload it to your Arduino UNO board.

2.  **Run the Data Logger:**
    Execute the `DHT-22 Data logger.py` script to begin logging data. The script will read serial data from the Arduino and record it.

### Note on the Pre-compiled Executable
> As I was carrying out the measurement on the borrowed laptop from another lab, which did not install python and not to mention the corresponding libraries, I assembled DHT-22_Data_logger.exe with pyinstall. >_> <br>
> However a problem that comes with this is that I cannot access the code easily anymore. TAT <br>
> I hard-coded SERIAL_PORT at "COM4" but just use DHT-22 Data logger.py if things goes wrong and change port number there...

> Anyways good luck w these ;D <br> -Edward
