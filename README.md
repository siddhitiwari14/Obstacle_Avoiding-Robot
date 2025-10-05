# Obstacle Avoiding Robot 🚗🤖  

An Arduino-based **Obstacle Avoiding Robot** that uses an **ultrasonic sensor** and a **servo motor** to detect obstacles and automatically change direction. The robot is powered by **Arduino with an Adafruit Motor Shield** and programmed to move forward, stop, reverse, or turn based on sensor readings.  

---

## 📌 Features  
- Autonomous movement with obstacle detection  
- Ultrasonic sensor mounted on a servo for left/right scanning  
- Smooth motor speed control with gradual acceleration  
- Automatic forward, backward, left, and right navigation  
- Works with **Adafruit Motor Shield** (AFMotor library)  

---

## 🛠️ Components Used  
- Arduino UNO 
- Adafruit Motor Shield  
- Ultrasonic Sensor (HC-SR04)  
- Servo Motor (for sensor rotation)  
- 2 × DC Motors with Wheels  
- Robot Chassis (cardboard)  
- Battery pack (12V recommended)  

---

## ⚙️ Working Principle  
1. The **ultrasonic sensor** mounted on a **servo** checks the front distance.  
2. If the path is clear → the robot moves **forward**.  
3. If an obstacle is detected within **15 cm** → the robot:  
   - Stops,  
   - Moves backward slightly,  
   - Rotates the servo left and right to check distances,  
   - Turns in the direction with more free space,  
   - Resumes forward motion.  

---

## 🔌 Circuit Connections  

<img width="3000" height="2534" alt="circuit_image" src="https://github.com/user-attachments/assets/1f1f29f4-dcbb-427a-ac0d-7ba9cc80ed92" />


## 🚀 How to Run  
1. Connect the components as per the wiring above.  
2. Install the required Arduino libraries:  
   - AFMotor  
   - NewPing  
   - Servo  
3. Upload the `.ino` code to your Arduino board.  
4. Power the robot using batteries.  
5. Place it on the ground and watch it **avoid obstacles**!  

---

## 📷 Demo  
![demo image](https://github.com/user-attachments/assets/39fe7b45-7444-4b84-adb6-617335351cd6)

 

---

## 📚 Applications  
- Autonomous robotics projects  
- Educational demonstrations  
- Robotics competitions  
- Smart vehicle prototypes  

---

## 🤝 Contributing  
If you’d like to improve this project, you can:  
- Add new features (Bluetooth, IR sensors, camera navigation, etc.)  
- Improve the documentation (README, wiring diagrams, images)  
- Fix bugs or optimize the code  

To contribute:  
1. Fork this repository.  
2. Make your changes.  
3. Submit a pull request

## 📞 Contact  
If you have any questions, suggestions, or collaboration ideas, feel free to reach out:  

- 📧 Email: tiwarisid0814@gmail.com   
- 🌐 LinkedIn: www.linkedin.com/in/siddhi-tiwari-821929252 

  
