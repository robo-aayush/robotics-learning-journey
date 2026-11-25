# 🗑️ Smart Dustbin

An Arduino-based dustbin that opens its lid automatically when someone comes near. No touching needed, so it is more hygienic.

## 🧰 Components
| Part | Quantity |
|------|----------|
| Arduino Uno | 1 |
| Ultrasonic sensor (HC-SR04) | 1 |
| Servo motor (SG90) | 1 |
| Breadboard | 1 |
| Jumper wires | As needed |
| 9V battery or USB power | 1 |

## ⚙️ How It Works
1. The ultrasonic sensor keeps measuring the distance in front of it.
2. When something comes within about 20 cm, the Arduino tells the servo to turn.
3. The servo lifts the lid (90 degrees).
4. After 3 seconds, the lid closes again.

## 📸 Photos and Trial Video
! [Parts used] (parts.jpeg)
! [Wiring and Setup] (wirings.jpeg)

Trial video: [trial.mp4] (trial.mp4)

## 🔌 Wiring
| Part | Pin | Arduino |
|------|-----|---------|
| Ultrasonic | VCC | 5V |
| Ultrasonic | GND | GND |
| Ultrasonic | Trig | Pin 9 |
| Ultrasonic | Echo | Pin 10 |
| Servo | Red (power) | 5V |
| Servo | Brown/Black (ground) | GND |
| Servo | Orange/Yellow (signal) | Pin 6 |

## 💻 Code
The Arduino code is in [smart-dustbin.ino](smart-dustbin.ino).

## 🚦 Status
🟡 In progress

## 📝 Progress
- [x] Idea and planning
- [x] Code written
- [ ] Collect components
- [ ] Test on breadboard
- [ ] Fit into dustbin
- [ ] Add photos and video

## 📚 What I Learned
- How an ultrasonic sensor measures distance
- How a servo motor is controlled by Arduino
- How to use GitHub to save my projects

(I will add more as I build.)

## 🔮 Future Ideas
- Add an LED or buzzer when the bin is full
- Add a second sensor to detect the bin level
- Use a battery with a power switch
