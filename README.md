# 🚀 CryptoTracker — Real-Time Cryptocurrency Dashboard

A modern Vue.js application that provides live cryptocurrency prices, interactive charts, portfolio tracking, and investment simulation — powered by **CoinCap API**, **Firebase Authentication**, and **Firestore**.

---

## ✨ Features

### 🔐 Authentication
- Secure Email/Password login (Firebase Auth)
- Login using **email OR username**
- User profile data stored in Firestore
- Smooth, multi-step registration UI

### 📊 Live Market
- Real-time cryptocurrency market data
- Sort by:
  - **Price Change %**
  - **24h Volume**
- Auto-updated values
- Color-coded indicators (green = positive, red = negative)

### 📈 Popular Coins Chart
- Beautiful interactive charts with Chart.js
- Time interval selector:
  - **1 Day (1DAY)**
  - **7 Days (7DAY)**
  - **1 Month (1MTH)**
- Smooth animations & responsive design

### 💼 Portfolio Management
- Track invested coins
- Calculate portfolio value
- View coin performance historically

### 💸 Investment Simulation
- Modal for quick coin investment simulation
- Dynamic calculations based on real prices

### 🎨 Modern UI
- Fully responsive layout
- Dark mode design
- TailwindCSS for clean and elegant styling

---

## 🛠️ Tech Stack

### **Frontend**
- Vue 3 (Composition API)
- Vue Router
- Pinia (state management)
- TailwindCSS
- Chart.js + vue-chartjs

### **Backend / Services**
- Firebase Authentication
- Firebase Firestore

### **External API**
- CoinCap API (Market data & Historical charts)
