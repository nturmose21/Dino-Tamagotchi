# HACK_UPDT DINO Tamaguino

Tamaguino is a Tamagotchi-style virtual pet game for Arduino.  
It runs on an SSD1306 OLED display and uses physical buttons for interaction.  
Feed, play with, and care for your pet to keep it happy and healthy!

---

## 📷 Features
- Virtual pet simulation with hunger, happiness, and health stats
- Splash screen on startup
- OLED graphics for the pet and menus
- Button controls for feeding, playing, and cleaning
- Optional buzzer for sound effects

---

## 🛠 Hardware Requirements
- Arduino Nano, Uno, or compatible board
- SSD1306 I2C OLED display (128x64)
- 3 push buttons
- 1 piezo buzzer (optional)
- Breadboard and jumper wires

---

## 🔌 Wiring

| Component      | Arduino Pin |
|----------------|-------------|
| **OLED SDA**   | A4          |
| **OLED SCL**   | A5          |
| **Button 1**   | 7           |
| **Button 2**   | 9           |
| **Button 3**   | 12          |
| **Buzzer**     | 13          |
| **VCC (OLED)** | 5V          |
| **GND (OLED)** | GND         |

_Note: Buttons should be wired with pull-down resistors or use `INPUT_PULLUP` mode._

---

## 📦 Required Libraries
Install these via the Arduino Library Manager:
- **Adafruit SSD1306**  
- **Adafruit GFX Library**

---

## ▶ How to Play
- **Button 1** – Feed your pet  
- **Button 2** – Play with your pet  
- **Button 3** – Clean up after your pet  
- Keep your pet’s stats in the green to keep it alive and happy.

---

## 🚀 Getting Started
1. Clone or download this repository.
2. Open `Tamaguino.ino` in the Arduino IDE.
3. Install the required libraries.
4. Upload to your Arduino board.
5. Have fun taking care of your Tamaguino!

---

## 📄 License
This project is open-source under the MIT License.  
Feel free to modify and share it.

---
