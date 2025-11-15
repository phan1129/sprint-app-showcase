
# 🏁 Sprint – AI-Powered Goal Execution App (Showcase Overview)

> **Transform big goals into actionable weekly plans with AI-powered task breakdown and intelligent scheduling.**

Sprint is an iOS productivity app designed for busy professionals who want to achieve meaningful goals without overwhelm.  
The app converts quarterly goals into structured weekly tasks, automatically schedules “golden hour” work blocks, and provides a clean minimal UI inspired by Apple and Notion.

This repository is a **public showcase** of the Sprint project for recruiters and collaborators.  
👉 **The full source code is private, but available upon request.**

---

## 🚀 Key Features (Phase 1–2 Complete)

### ✔ SwiftUI Foundation Architecture
- Clean modular structure  
- DesignSystem for colors, spacing, typography  
- Reusable UI components (buttons, inputs, cards)  
- AppCoordinator-based navigation  

### ✔ Supabase Integration
- Email/password authentication  
- Session persistence  
- RLS-ready database  
- Secure backend integration  

### ✔ Authentication Experience
- Welcome screen  
- Sign Up  
- Login  
- Input validation  
- Friendly error handling  
- Smooth loading states  

### ✔ Upcoming Features (In Progress)
- AI-powered task breakdown  
- Auto-scheduling with user availability  
- Task cards + weekly planning  
- Dashboard home screen  
- Animations, charts, progress tracking  

---

## 📱 Screens (Preview)
<img width="438" height="912" alt="Screenshot 2025-11-14 at 5 47 31 PM" src="https://github.com/user-attachments/assets/f8fc88c2-4e10-4360-99e3-0f874f98203f" />
<img width="438" height="912" alt="Screenshot 2025-11-14 at 5 48 08 PM" src="https://github.com/user-attachments/assets/0b2a329f-e0fc-4f4f-9a11-f6dd9846d683" />
<img width="438" height="912" alt="Screenshot 2025-11-14 at 5 48 18 PM" src="https://github.com/user-attachments/assets/6d9bb01f-2078-4819-b831-91a44173e445" />

---

## 🏗️ Architecture Overview
Sprint/
├── App/
│   └── SprintApp.swift
├── Core/
│   ├── Networking/
│   │   ├── SupabaseManager.swift
│   │   └── AuthManager.swift
│   ├── Utilities/
│   │   └── AppCoordinator.swift
│   └── Config.swift
├── Features/
│   ├── Auth/
│   │   ├── WelcomeView.swift
│   │   ├── LoginView.swift
│   │   └── SignUpView.swift
│   ├── Onboarding/
│   └── Home/
├── Components/
│   ├── Buttons/
│   ├── Inputs/
│   └── Cards/
└── Resources/
    └── DesignSystem.swift

---

## 🧠 Tech Stack

- **Swift 5.9**
- **SwiftUI**
- **Supabase**
- **Combine**
- **iOS 17+**
- **Xcode 15+**

---

## 👤 About the Builder

**Patrick Han — Product Manager & Builder**

- Designed the technical architecture  
- Built the entire SwiftUI frontend  
- Integrated Supabase authentication  
- Designed onboarding + future goal planning flows  
- Leading development of AI-powered task system  

---

## 📌 Project Status

| Phase | Description | Status |
|-------|-------------|--------|
| Phase 1 | Foundation setup | ✅ Complete |
| Phase 2 | Authentication | ✅ Complete |
| Phase 3 | Onboarding flow | 🚧 In progress |
| Phase 4 | Task engine + scheduling | 🔜 Next |
| Phase 5 | Polished UI | 🔜 Upcoming |

---

## 🔒 Why the Full Repo is Private

- Supabase keys and backend logic included  
- Protects production database  
- Prevents misuse or cloning  
- Ensures a controlled development environment  

👉 **Recruiters**: Full source available upon request.  
Email: **patrickjjhan@gmail.com**

---

## 📫 Contact

**Email:** patrickjjhan@gmail.com  
**GitHub:** https://github.com/phan1129  
**LinkedIn:** https://www.linkedin.com/in/patrick-han-product1/

---

## ⭐ Note to Recruiters

This repo summarizes:
- Architecture decisions  
- Technical complexity  
- Real-world Swift development  
- Project leadership & execution  

Happy to walk through the full Sprint app or grant read-only access upon request.

---
