# Final Android App – Erasmus Mobility Companion

> Mobile Android application developed as part of an engineering project in the Computer Science specialization.  
> This app is designed to assist students from our school in preparing and navigating their international exchanges (e.g., through the Erasmus+ programme).

---

## Table of contents  
- [Overview](#overview)  
- [App Concept & Features](#app-concept--features)  
- [Repository Structure](#repository-structure)  
- [Technologies & Requirements](#technologies--requirements)  
- [Installation & Build](#installation--build)  
- [Usage](#usage)  
- [Expected Outcomes](#expected-outcomes)  
- [Learning Goals](#learning-goals)  
- [Contributing](#contributing)  
- [License](#license)  
- [Author](#author)  

---

## Overview  
This project is a mobile Android application created to help students from our engineering school prepare for and make the most of their exchange programmes (such as Erasmus+). The app offers city‑guides, partner‑school information, tips on student life abroad, and interactive features to keep track of essential steps (visa, accommodation, language prep, etc.).  

---

## App Concept & Features  
Key features of the app include:  
- A list of partner schools and cities, including maps, photos and student tips.  
- “Good plans” section where users can share local deals, student discounts, and favourite places in partner cities.  
- Checklist planner for exchange preparation (administrative tasks, packing list, arrival schedule).  
- Push notifications or reminders for key deadlines (applications, housing contracts, orientation sessions).  
- (Optional) Forum or comments section where previous exchange students share advice.  

Target users: students from our school preparing for international mobility. The goal is to offer a smooth, guided experience via mobile, tailored to the engineering context.

---

## Repository Structure  
Example structure (adapt according to your actual directory names):  

```
.
├── app/                          # Android Studio project folder
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/             # Java or Kotlin source files
│   │   ├── res/                  # Resources: layouts, drawables, values
│   └── build.gradle              
├── data/                         # Sample data, city info, partner‑schools JSON
├── docs/                         # Design docs, mock‑ups, user flows
│   └── Final_Android_App_Erasmus_Report.pdf
├── README.md                     # This file
└── LICENSE                       # License file
```

---

## Technologies & Requirements  
- Android Studio (version 4.0+ recommended)  
- Android SDK (API level 21 or newer)  
- Kotlin (or Java, depending on implementation)  
- Google Maps SDK for Android (if map features used)  
- JSON or SQLite for local data storage  
- Optional: Firebase for backend, push notifications or analytics  

---

## Installation & Build  
1. Clone the repository:  
   ```bash
   git clone https://github.com/victorpiana/Final_Android_App_Erasmus.git
   cd Final_Android_App_Erasmus
   ```  
2. Open the project in Android Studio.  
3. Ensure you have the required SDKs installed (check `build.gradle` for version).  
4. Build the app and install on a device or emulator:  
   ```bash
   ./gradlew installDebug
   ```  
5. (Optional) Create a signed APK for release via Build → Generate Signed Bundle / APK in Android Studio.

---

## Usage  
After installation, the user can:  
- Browse the list of partner schools and cities.  
- Tap on a city to view student tips, discounts and local favourites.  
- Check off items in the exchange preparation checklist.  
- View notifications for upcoming deadlines (if enabled).  
- Submit their own “good plan” for a city (if data submission implemented).  

---

## Expected Outcomes  
By using this app, students should be better prepared for their exchange experience:  
- Know the partner schools and host cities ahead of time.  
- Have access to local tips and student‑shared “good deals”.  
- Have a clear checklist and timeline of tasks to complete.  
- Feel more confident arriving in a new environment thanks to mobile guidance.  

---

## Learning Goals  
Through this project I learned and practiced:  
- Android mobile development (UI, navigation, data storage).  
- Integrating mapping and location features (e.g., Google Maps).  
- Designing user‑centred mobile interfaces for student mobility.  
- Working with local data (JSON/SQLite), app lifecycle, and mobile UX considerations.  

---

## Contributing  
Your contributions are welcome! You can:  
- Add new partner cities or schools (update the data in `data/`).  
- Improve UI/UX, add animations or dark mode.  
- Add backend features (e.g., Firebase) for shared data or analytics.  
- Report issues or suggest improvements via GitHub pull requests.

To contribute:  
1. Fork the repository  
2. Create a branch (`git checkout -b feat/my‑feature`)  
3. Commit changes, update documentation, and open a pull request  

---

## License  
This project is licensed under the **MIT License**. See the `LICENSE` file for details.  

---

## Author  
**Victor Piana**  
Engineering student - Computer Science
