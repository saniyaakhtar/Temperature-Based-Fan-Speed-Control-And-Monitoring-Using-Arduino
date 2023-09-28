# Temperature-Based Fan Speed Control and Monitoring Project

## Description
This project is a standalone automatic fan speed controller that regulates the speed of an electric fan based on temperature requirements. It utilizes embedded technology to create an efficient and reliable closed-loop feedback control system. The heart of the system is the ATMega8/168/328 microcontroller (MCU), which enables dynamic and precise control. The 16x2 LCD panel provides a user-friendly interface by displaying both the sensed temperature and fan speed levels simultaneously.

This compact project can find applications in various scenarios, including air-conditioners, water heaters, snow melters, ovens, heat exchangers, mixers, furnaces, incubators, thermal baths, and veterinary operating tables. By intelligently adjusting fan speed, it helps conserve energy and electricity.

## Components
Here is a list of components used in this project:

- **Board1 (Arduino Uno):** The central microcontroller that controls all functions.
- **LCD1 (16x2 LCD):** The display unit for showing temperature and fan speed.
- **IC1 (LM35 Temperature Sensor):** A precision temperature sensor that converts temperature into an electrical signal.
- **D1 (BD139 NPN Transistor, 1N4007 Diode):** Components used for fan speed control.
- **LED1 (5mm LED):** Indicator for system status.
- **R1, R2 (1-kilo-ohm Resistors):** Resistors used in the circuit.
- **R3 (470-ohm Resistor):** Another resistor in the circuit.
- **VR1 (10-kilo-ohm Preset Resistor):** A variable resistor for calibration.
- **C1 (10uF, 16V Electrolytic Capacitor):** Capacitor used in the circuit.
- **2-pin Terminal Connector:** Component for connecting external devices.
- **3-pin Connector:** Connector for external connections.
- **8-pin Connector:** Connector for external connections.
- **MI (12V DC Fan, 12V Battery):** The fan and its power source.

## Working Principle
The project relies on the ATMega8/168/328 microcontroller (Board1) and the LM35 temperature sensor (IC1) to control fan speed based on the sensed temperature. The LM35 sensor converts temperature into an analog signal, which is then processed by the MCU through an analog-to-digital converter (ADC). The MCU displays the temperature and fan speed on the 16x2 LCD (LCD1).

To control fan speed, a low-frequency pulse-width modulation (PWM) signal is employed. This PWM signal, typically around 30Hz, varies in duty cycle to adjust the fan's speed. A BD139 NPN transistor (D1) is used to efficiently control the fan motor.

## Use Cases
1. **Air Conditioner:** Regulate the speed of a fan in an air conditioning system to maintain the desired temperature in a room.
2. **Water Heater:** Control fan speed in a water heater to optimize heating and save energy.
3. **Snow Melter:** Prevent snow accumulation on surfaces by adjusting the fan speed based on temperature.
4. **Oven:** Ensure precise temperature control in an oven for cooking or baking.
5. **Heat Exchanger:** Optimize heat exchange processes by adjusting fan speed.
6. **Mixer:** Control fan speed in a mixer to avoid overheating during operation.
7. **Furnace:** Regulate fan speed in a furnace for efficient heating.
8. **Incubator:** Maintain a stable temperature in an incubator for scientific or biological applications.
9. **Thermal Bath:** Control the temperature in a thermal bath for relaxation and therapeutic purposes.
10. **Veterinary Operating Table:** Ensure a comfortable temperature for animals during surgical procedures.

This project not only provides efficient temperature-based fan speed control but also has the potential to save energy and electricity in various applications.
