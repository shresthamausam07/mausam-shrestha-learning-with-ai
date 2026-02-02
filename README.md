# Mausam Shrestha - Learning with AI

Documentation of my learning journey with AI assistance for IoT development during Spring 2026.

## Overview

This repository tracks my self-directed learning with AI assistance (primarily Claude) as I develop the Smart Home Health Monitor project. I am learning two domains:
1. **Software Domain**: Mobile App Development with React Native
2. **Hardware Domain**: Multi-Sensor Integration & Calibration

The goal is to demonstrate that software engineers are forever learners, and AI can be a powerful tool for acquiring new technical skills efficiently.

---

## Learning Topic 1: Mobile App Development with React Native

### Why I Need to Learn This

**Project Requirement**: My Smart Home Health Monitor needs a mobile application for users to:
- View real-time air quality readings remotely
- Receive push notifications for air quality alerts
- Access historical data and trends
- Log sleep quality ratings
- Control purifier settings from anywhere

**Personal Gap**: I have limited experience with mobile app development. While I know web development basics, creating native mobile apps with proper navigation, state management, and push notifications is new territory.

**Career Relevance**: Mobile development is crucial for IoT products. Most smart home devices require companion apps, and React Native enables building for both iOS and Android from a single codebase, making it highly practical.

### What I Will Learn

**Core Concepts**:
1. React Native fundamentals (components, props, state)
2. Navigation (React Navigation library)
3. State management (Context API or Redux)
4. Asynchronous operations and API integration
5. Push notifications (Firebase Cloud Messaging)
6. Data visualization on mobile (charts and graphs)
7. Local storage (AsyncStorage)
8. Progressive Web App (PWA) as alternative approach

**Specific Technologies**:
- React Native framework
- Expo (development toolchain)
- Firebase SDK for mobile
- Chart.js or Victory for data visualization
- React Native Push Notifications

**Deliverables**:
- Functional mobile app (PWA initially, React Native later)
- Real-time dashboard with sensor readings
- Historical data visualization
- Push notification system
- Sleep quality logging interface

### How I Will Learn It with AI

**Learning Strategy**:

1. **Conceptual Understanding** (Weeks 1-2)
   - Ask Claude to explain React Native architecture
   - Compare React Native vs native development vs PWA
   - Understand component lifecycle and state management
   - Learn navigation patterns in mobile apps

2. **Hands-On Development** (Weeks 3-6)
   - Use AI to scaffold initial project structure
   - Get help debugging errors and understanding error messages
   - Ask for code examples and best practices
   - Request explanations of documentation when unclear

3. **Problem Solving** (Weeks 7-10)
   - Debug issues with API integration
   - Optimize performance with AI suggestions
   - Implement push notifications with guidance
   - Design responsive UI layouts with feedback

4. **Code Review & Optimization** (Weeks 11-12)
   - Ask AI to review my code for improvements
   - Learn optimization techniques
   - Understand security best practices
   - Refactor code for maintainability

**AI Interaction Examples**:
- "Explain how to set up React Native with Expo"
- "Why is my component not re-rendering when state changes?"
- "Show me how to implement tab navigation"
- "How do I integrate Firebase push notifications?"
- "Review this code and suggest improvements"

**Progress Tracking**:
- Weekly journal entries documenting what I learned
- Code snippets with AI explanations
- Before/after comparisons of code improvements
- Screenshots of working features

---

## Learning Topic 2: Multi-Sensor Integration & Calibration

### Why I Need to Learn This

**Project Requirement**: My Smart Home Health Monitor uses 5 different sensors:
- MH-Z19B (CO2) - UART protocol
- PMS5003 (PM2.5) - UART protocol
- SGP40 (VOC) - I2C protocol
- AHT20 (Temp/Humidity) - I2C protocol
- OLED Display - I2C protocol

**Technical Challenge**: Each sensor uses different communication protocols, requires specific initialization sequences, and needs calibration to provide accurate readings. Research shows that low-cost sensors have significant accuracy challenges without proper calibration.

**Learning Gap**: While I understand basic Arduino programming, I have limited experience with:
- Managing multiple UART devices
- I2C addressing and bus conflicts
- Sensor calibration techniques
- Signal processing and noise reduction
- Compensating for environmental factors (temperature, humidity)

### What I Will Learn

**Hardware Communication**:
1. UART protocol and serial communication
2. I2C bus architecture and addressing
3. Managing multiple sensors on shared buses
4. Handling sensor initialization and timing
5. Error detection and recovery

**Sensor Calibration**:
1. Understanding sensor datasheets
2. Baseline calibration procedures
3. Cross-calibration techniques
4. Environmental compensation algorithms
5. Kalman filters for noise reduction
6. Moving averages and signal smoothing

**Specific Skills**:
- Reading and interpreting sensor datasheets
- Implementing sensor drivers in C++
- Debugging hardware communication issues
- Using oscilloscope/logic analyzer (if available)
- Applying statistical methods for calibration
- Implementing AutoML-driven calibration (based on 2026 research)

**Deliverables**:
- Working sensor drivers for all 5 sensors
- Calibration procedures documented
- Accuracy within ±20% of reference monitors
- Noise reduction algorithms implemented
- Comprehensive testing results

### How I Will Learn It with AI

**Learning Strategy**:

1. **Datasheet Analysis** (Weeks 1-2)
   - Upload sensor datasheets to AI
   - Ask for explanations of timing diagrams
   - Understand register configurations
   - Learn communication protocol requirements

2. **Implementation Guidance** (Weeks 3-4)
   - Get help writing sensor driver code
   - Debug communication issues
   - Understand library implementations
   - Resolve I2C address conflicts

3. **Calibration Research** (Weeks 5-7)
   - Ask AI to summarize calibration research papers
   - Learn statistical methods for sensor correction
   - Understand AutoML calibration approaches
   - Implement Kalman filters with guidance

4. **Troubleshooting** (Weeks 8-10)
   - Debug sensor reading anomalies
   - Identify sources of noise and drift
   - Optimize sampling rates
   - Improve accuracy with AI suggestions

5. **Documentation** (Weeks 11-12)
   - Create calibration procedures
   - Document accuracy testing results
   - Write hardware setup guides
   - Compile lessons learned

**AI Interaction Examples**:
- "Explain this timing diagram from the MH-Z19B datasheet"
- "Why am I getting garbage data from my UART sensor?"
- "How do I implement a Kalman filter for CO2 readings?"
- "What causes I2C bus conflicts and how do I fix them?"
- "Explain the AutoML calibration approach from this research paper"

**Progress Tracking**:
- Sensor bring-up logs (what worked, what didn't)
- Calibration data and accuracy measurements
- Code snippets with explanations
- Hardware debugging session notes
- Before/after calibration comparison graphs

---

## Weekly Learning Log

### Week 1: [Date]
**Topics Covered**:
- [What I learned]

**AI Interactions**:
- [Key questions asked and insights gained]

**Challenges**:
- [Problems encountered and how I solved them]

**Code Examples**:
```
[Code snippets with explanations]
```

**Next Steps**:
- [What I plan to learn next week]

---

### Week 2: [Date]
[To be filled]

---

## AI Tools Used

**Primary AI Assistant**:
- **Claude (Anthropic)**: Main learning companion for explanations, code generation, debugging, and concept clarification

**Secondary Tools**:
- ChatGPT: Alternative perspectives on complex problems
- GitHub Copilot: Code completion and suggestions
- Perplexity AI: Research paper summaries

---

## Learning Outcomes Assessment

### Mobile App Development
**Before**:
- [ ] Understanding of React Native architecture
- [ ] Knowledge of mobile navigation patterns
- [ ] Experience with state management
- [ ] Ability to implement push notifications
- [ ] Skills in mobile data visualization

**After** (To be assessed at end of semester):
- [ ] Built functional mobile app from scratch
- [ ] Implemented complex navigation flows
- [ ] Managed state effectively
- [ ] Integrated push notifications
- [ ] Created responsive, data-rich interfaces

### Multi-Sensor Integration & Calibration
**Before**:
- [ ] Understanding of UART protocol
- [ ] Knowledge of I2C bus architecture
- [ ] Experience with sensor calibration
- [ ] Skills in signal processing
- [ ] Ability to interpret datasheets

**After** (To be assessed at end of semester):
- [ ] Successfully integrated 5+ sensors
- [ ] Achieved ±20% accuracy target
- [ ] Implemented calibration algorithms
- [ ] Applied noise reduction techniques
- [ ] Created reusable sensor drivers

---

## Resources & References

### Mobile App Development
- React Native Documentation: https://reactnative.dev/
- Expo Documentation: https://docs.expo.dev/
- React Navigation: https://reactnavigation.org/
- Firebase React Native: https://rnfirebase.io/

### Hardware & Sensors
- [DIY Air Quality Monitor Tutorial](https://howtomechatronics.com/projects/diy-air-quality-monitor-pm2-5-co2-voc-ozone-temp-hum-arduino-meter/)
- [AutoML Calibration Research (2026)](https://amt.copernicus.org/articles/19/603/2026/)
- [EPA Sensor Placement Guide](https://www.epa.gov/air-sensor-toolbox/guide-siting-and-installing-air-sensors)
- Sensor datasheets (stored in /datasheets directory)

---

## Reflection & Insights

### What Worked Well
[To be filled at end of semester]

### What Was Challenging
[To be filled at end of semester]

### How AI Helped My Learning
[To be filled at end of semester]

### Advice for Future Learners
[To be filled at end of semester]

---

## Author

**Mausam Shrestha**
- GitHub: [@shresthamausam07](https://github.com/shresthamausam07)
- Course: CSC 494 - IoT (Spring 2026)
- Institution: Northern Kentucky University
- Project Repository: [smart-home-health-monitor](https://github.com/shresthamausam07/smart-home-health-monitor)

---

**Last Updated**: February 1, 2026
