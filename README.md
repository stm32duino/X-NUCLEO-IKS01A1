# X-NUCLEO-IKS01A1

The X-NUCLEO-IKS01A1 is a motion MEMS and environmental sensor expansion board for the STM32 Nucleo.
It is equipped with Arduino UNO R3 connector layout, and is designed around the LSM6DS0 3D accelerometer and 3D gyroscope, 
the LIS3MDL 3D magnetometer, the HTS221 humidity and temperature sensor and the LPS25HB pressure sensor.
The X-NUCLEO-IKS01A1 interfaces with the STM32 microcontroller via the I²C pin, and it is possible to change the default I²C port.

## Examples

There are several examples with the X-NUCLEO-IKS01A1 library.
* X_NUCLEO_IKS01A1_HelloWorld: This application provides a simple example of usage of the X-NUCLEO-IKS01A1 
Expansion Board. It shows how to display on a hyperterminal the values of all on-board MEMS and environmental sensors.
* X_NUCLEO_IKS01A1_6DOrientation: This application shows how to use X-NUCLEO-IKS01A2 to find out the 6D orientation and 
display data on a hyperterminal (only with LSM6DS3).
* X_NUCLEO_IKS01A1_DoubleTap: This application shows how to detect the double tap event using the X-NUCLEO-IKS01A2 (only with LSM6DS3).
* X_NUCLEO_IKS01A1_FreeFall: This application shows how to detect the free fall event using the X-NUCLEO-IKS01A2 (only with LSM6DS3).
* X_NUCLEO_IKS01A1_MultiEvent: This application shows how to detect free fall, tap, double tap, tilt, wake up,
6D Orientation and step events using the X-NUCLEO-IKS01A2 (only with LSM6DS3).
* X_NUCLEO_IKS01A1_Pedometer: This application shows how to use X-NUCLEO-IKS01A2 to count steps (only with LSM6DS3).
* X_NUCLEO_IKS01A1_Tap: This application shows how to detect the single tap event using the X-NUCLEO-IKS01A2 (only with LSM6DS3).
* X_NUCLEO_IKS01A1_Tilt: This application shows how to detect the tilt event using the X-NUCLEO-IKS01A2 (only with LSM6DS3).
* X_NUCLEO_IKS01A1_WakeUp: This application shows how to detect the wake-up event using the X-NUCLEO-IKS01A2 (only with LSM6DS3).

## Dependencies

The X-NUCLEO-IKS01A1 library requires the following STM32duino libraries:

* STM32duino LSM6DS0: https://github.com/stm32duino/LSM6DS0
* STM32duino LSM6DS3: https://github.com/stm32duino/LSM6DS3
* STM32duino LIS3MDL: https://github.com/stm32duino/LIS3MDL
* STM32duino HTS221: https://github.com/stm32duino/HTS221
* STM32duino LPS25HB: https://github.com/stm32duino/LPS25HB


## Notes

In order to use LSM6DS3 on X-NUCLEO-IKS01A1 board you need the STEVAL-MKI160V1 board attached to X-NUCLEO-IKS01A1 board 
via DIL24 interface.

## Documentation

You can find the source files at  
https://github.com/stm32duino/X-NUCLEO-IKS01A1

The X-NUCLEO-IKS01A1 datasheet is available at  
http://www.st.com/content/st_com/en/products/ecosystems/stm32-open-development-environment/stm32-nucleo-expansion-boards/stm32-ode-sense-hw/x-nucleo-iks01a1.html
