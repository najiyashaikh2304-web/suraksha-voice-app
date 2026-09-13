# Suraksha Voice App - 4 Layer Safety System
**College Project by Najiya Shaikh | Beed, Maharashtra**

### 📌 Project Overview
Suraksha Voice is a women safety + accident detection app with 4 different emergency triggers. If any one condition is met, it automatically sends help.

### ✨ 4 Working Conditions (Emergency Triggers)

**CONDITION 1: Voice Activated SOS**
- When user says loudly "HELP HELP" or "BACHAO"
- Speech Recognizer sensor listens for keyword.
- Action: Sends Live Location + "I am in danger, need help" SMS to family.

**CONDITION 2: Shake to Alert (For Unsafe Situation)**
- When girl cannot speak loudly.
- If she shakes her phone continuously for 3-4 times within 5 seconds.
- Action: Silent SMS with location goes to parents without making any sound.

**CONDITION 3: Accident Detection (NEW Feature)**
- Uses Accelerometer Sensor.
- If sudden high force is detected (Speed > 25 m/s², like bike fall / car accident).
- Action: 
  Step A - Phone starts vibrating + 10 sec countdown starts
  Step B - If user is OK, she can press CANCEL button
  Step C - If not cancelled, it auto sends "ACCIDENT ALERT! I met with accident" + Google Maps link.

**CONDITION 4: One-Tap SOS & Fake Call Button**
- Big Red SOS Button on main screen.
- One tap = Instant SOS SMS.
- Long Press = Fake Incoming Call from "Papa" to escape uncomfortable place (auto rickshaw, etc).

### 🛠️ Technology Used
- MIT App Inventor 2
- Sensors: SpeechRecognizer, Accelerometer, LocationSensor, Pedometer (for shake)
- Components: Texting, Sound, Clock Timer, Notifier

### 🎯 Working Logic Summary
App always runs in background -> Checks 4 conditions parallelly ->
IF (Voice = HELP) OR (Shake Count >=3) OR (Acceleration > 25) OR (SOS Button Pressed) 
THEN -> Get Location -> Send SMS to 3 Emergency Contacts.

### 👩‍💻 Future Scope
- Auto call to 112 / 108 Ambulance
- Connect to nearby Police Station API

---
Mini Project 2026 - Savitribai Phule Pune University# suraksha-voice-app
Woman safety app for college project 
