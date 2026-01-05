# Influensa AI ✨

**Influensa AI** is a mobile application that generates **photorealistic AI influencer images** for marketing, social media, and creative use cases.

Users can customize ethnicity, hair color, scene, and optionally provide a **product reference image** to generate realistic influencer-style visuals.

---

## 🚀 Features

- 📸 Photorealistic AI influencer image generation  
- 🎭 Ethnicity, hair color, and scene customization  
- 👜 Optional product image reference (accurate representation)  
- 🔐 Secure authentication with Google Sign-In (Firebase Auth)  
- ☁️ Cloud-based image generation and storage  
- ⚡ Credit-based usage system (prevents abuse)  
- 🌙 Dark theme, modern mobile UI  

---

## 🧠 Tech Stack

### Frontend
- Expo (React Native)
- Expo Router
- NativeWind (Tailwind-style UI)
- Firebase Auth (Google Sign-In)
- Firebase Functions (Callable)
- Firebase Storage
- Firebase Firestore

### Backend
- Firebase Cloud Functions (v2)
- Google Gemini Image Models
- Firebase Admin SDK

---

## 🔐 Authentication

Influensa AI uses **Google Sign-In** via Firebase Authentication.

- No passwords are stored by the app
- Authentication tokens are securely handled by Firebase
- Each user is uniquely identified by their Firebase `uid`

---

## 💳 Credits System

- Each image generation consumes **1 credit**
- Credits are managed **server-side only**
- Free users receive a limited number of credits
- Credits cannot be modified from the client
- Pro subscription support planned (RevenueCat)

---

## ☁️ Data Storage

- Generated images are stored in **Firebase Storage**
- Metadata is stored in **Firestore**
- User data is isolated per authenticated user
- Preset images are publicly readable, user-generated images are private

---

## 🛡 Privacy & Safety

- No images are generated involving minors
- No explicit or sexual content
- Product images are not altered or redesigned
- The app is compliant with App Store & Google Play policies

👉 Read the full [Privacy Policy](./PRIVACY_POLICY.md)

---

## 📄 Terms of Service

By using Influensa AI, users agree to the app’s terms regarding usage, content generation, and limitations.

👉 Read the full [Terms of Service](./TERMS_OF_SERVICE.md)

---

## 🧪 Development Notes

- This app requires **Expo Dev Client / EAS Build**
- Expo Go is **not supported** due to native authentication
- Environment variables are required for API keys
- Firebase emulators are supported for local development

---

## 📬 Contact

For questions or support:

**Email:** ozcanz aferayan@gmail.com  
**GitHub:** https://github.com/ozcanzaferayan

---

## ⚠️ Disclaimer

Influensa AI generates AI-created images for creative and marketing purposes only.  
Generated images should not be used to misrepresent real individuals.

---

© 2026 Influensa AI. All rights reserved.
