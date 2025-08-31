# 🎶 React Module Federation - Music MFE Assignment

This project demonstrates **Micro Frontend (MFE)** architecture using **React + Webpack Module Federation**.  
It consists of two separate applications:

1. **Main App (Host)** → Loads the remote micro frontend.  
2. **Music MFE (Remote)** → Provides a Music Library component exposed to the host.

---
## ✅ Features

- Microfrontend architecture with **Module Federation**
- Independent build and deployment for each app
- Shared **react** and **react-dom** dependencies
- Dynamic remote component loading

---

## 📦 Tech Stack

- **React**
- **Webpack 5**
- **Module Federation**
- **Babel**

---
## ScreenShot
![Screenshot](https://raw.githubusercontent.com/vik802207/Finacplus-Assign/main/a/Screenshot%20(794).png)
![Screenshot](https://raw.githubusercontent.com/vik802207/Finacplus-Assign/main/a/Screenshot%20(795).png)
![Screenshot](https://raw.githubusercontent.com/vik802207/Finacplus-Assign/main/a/Screenshot%20(796).png)
![Screenshot](https://raw.githubusercontent.com/vik802207/Finacplus-Assign/main/a/Screenshot%20(797).png)
![Screenshot](https://raw.githubusercontent.com/vik802207/Finacplus-Assign/main/a/Screenshot%20(798).png)
![Screenshot](https://raw.githubusercontent.com/vik802207/Finacplus-Assign/main/a/Screenshot%20(799).png)
![Screenshot](https://raw.githubusercontent.com/vik802207/Finacplus-Assign/main/a/Screenshot%20(800).png)
![Screenshot](https://raw.githubusercontent.com/vik802207/Finacplus-Assign/main/a/Screenshot%20(801).png)
![Screenshot](https://raw.githubusercontent.com/vik802207/Finacplus-Assign/main/a/Screenshot%20(802).png)
![Screenshot](https://raw.githubusercontent.com/vik802207/Finacplus-Assign/main/a/Screenshot%20(803).png)
![Screenshot](https://raw.githubusercontent.com/vik802207/Finacplus-Assign/main/a/Screenshot%20(804).png)
![Screenshot](https://raw.githubusercontent.com/vik802207/Finacplus-Assign/main/a/Screenshot%20(805).png)
![Screenshot](https://raw.githubusercontent.com/vik802207/Finacplus-Assign/main/a/Screenshot%20(806).png)
![Screenshot](https://raw.githubusercontent.com/vik802207/Finacplus-Assign/main/a/Screenshot%20(807).png)
![Screenshot](https://raw.githubusercontent.com/vik802207/Finacplus-Assign/main/a/Screenshot%20(808).png)
![Screenshot](https://raw.githubusercontent.com/vik802207/Finacplus-Assign/main/a/Screenshot%20(809).png)
![Screenshot](https://raw.githubusercontent.com/vik802207/Finacplus-Assign/main/a/Screenshot%20(810).png)
![Screenshot](https://raw.githubusercontent.com/vik802207/Finacplus-Assign/main/a/Screenshot%20(811).png)
![Screenshot](https://raw.githubusercontent.com/vik802207/Finacplus-Assign/main/a/Screenshot%20(812).png)
![Screenshot](https://raw.githubusercontent.com/vik802207/Finacplus-Assign/main/a/Screenshot%20(813).png)
---

## 📂 Project Structure
```bash
FinacPlus/
│── main-app/          # Host application (container)
│   ├── src/
│   │   └── App.js
│   ├── webpack.config.js
│   └── package.json
│
│── music-lib/      # Remote micro-frontend
│   ├── src/
│   │   └── MusicLibrary.js
│   ├── webpack.config.js
│   └── package.json
```
## 🚀 Getting Started
### 1️⃣ Clone the repo & install dependencies
 ```bash
git clone https://github.com/vik802207/Finacplus-Assign
```
Install dependencies for both apps:
```bash
cd main-app
npm install
cd ../music-lib
npm install
```
### 2️⃣ Run the apps
```bash
First, start the musicLibrary (remote):
cd music-lib
npm run build
```
```bash
Then, start the main-app (host) in another terminal:
cd main-app
npm start
```
## 📜 License
This project is licensed under the **MIT License** – you are free to use, modify, and distribute this project with proper attribution.  

---

## 👨‍💻 Author
Made with by **Vikash Gupta**  
📧 Email: [vikashg802207@gmail.com](mailto:vikashg802207@gmail.com)  


