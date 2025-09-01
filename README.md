# AIWatchWider

AIWatchWider is an **AI-powered luxury watch winder cabinet** designed for watch collectors.  
The system combines **hardware (Raspberry Pi, actuators, sensors)** and **software (Android app, state machine, UI/UX)** to provide a seamless way of storing, winding, and retrieving watches in a luxury furniture design.

---

## 🚀 Project Vision
Luxury watches deserve more than storage. AIWatchWider:
- Serves watches on demand (via touchscreen, voice, or mobile app).
- Uses an **intelligent state machine** to ensure safe operation.
- Provides **fail-safe mechanisms** to protect valuable watches.
- Combines **craftsmanship (wood, brass, glass)** with cutting-edge electronics.

---

## 📂 Repository Structure

```

AIWatchWider/
│
├── Documentation/                 # Project documentation
│   ├── Confluence\_Documentation/  # Exported Confluence pages
│   │   ├── Product/               # Product requirements, features
│   │   ├── State\_Machine/         # State machine design
│   │   └── UI/                    # UI/UX specifications
│   └── State\_Machine\_Diagram/     # Draw\.io state machine diagrams
│
├── LICENSE                        # MIT License
└── README.md                      # You are here

```

---

## ⚙️ System Overview

- **Raspberry Pi Zero 2 W**: Runs the backend state machine and communicates with hardware.  
- **Android App (Samsung Tab A8 target)**: Frontend UI for watch selection and commands.  
- **USB Serial Communication**: JSON-based protocol between Android and Raspberry Pi.  
- **State Machine Logic**: Ensures safe sequencing of authentication, selection, command execution, and error handling.  

---

## 📜 Features (Work in Progress)

- 🔑 Fingerprint authentication (validated on Raspberry Pi, confirmed to UI).  
- 🕰️ Intelligent watch retrieval via rotating globe cabinet mechanism.  
- 🎤 Voice assistant integration (planned).  
- 🖥️ Full-screen kiosk-mode Android UI.  
- 🛡️ Safety-first design: retries, locks, and error recovery states.  

---

## 📖 Documentation

- **State Machine**: See [Documentation/State_Machine_Diagram](./Documentation/State_Machine_Diagram) for `.drawio` diagrams.  
- **Requirements & Specifications**: Tracked under `Confluence_Documentation`.  
- **UI Mockups**: Early concepts in `Documentation/Confluence_Documentation/UI`.  

---

## 🛠️ Current Development

- ✅ System state machine prototype in Python with GUI/CLI.  
- ✅ Repository initialized with documentation.  
- 🔄 Next: Android app (Kotlin + USB serial).  
- 🔮 Future: Hardware integration (actuators, sensors, cabinet design).  

---

## 📌 Roadmap

- [ ] Build hardware prototype (2–3 months)  
- [ ] Develop Android app with USB serial communication  
- [ ] Integrate JSON-based protocol  
- [ ] Add watch database management  
- [ ] Prepare investor demo  

---

## 📄 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Garen (@yesItsGaren)**  
Electronics engineer & test automation specialist, exploring the intersection of luxury, robotics, and AI.
```
