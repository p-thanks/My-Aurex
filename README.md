# 📚 My Aurex – College Management System

**My Aurex** is a full-stack college management system designed to streamline student registration, authentication, and profile management. Built with modern web technologies, it offers a responsive, user-friendly interface to simplify academic operations.

🌐 [**Live Demo:**]()

![MyCampus Demo](https://res.cloudinary.com/dhwpprvsb/image/upload/v1751170569/Screenshot_2025-06-29_at_9.21.32_AM_pkuglf.png)

---

## 🚀 Features

- 📝 **Student Registration & Login**: Secure sign-up and login with form validation.
- 🔐 **Password Security**: Toggle visibility for password input.
- 🎨 **Modern UI**: Clean, responsive design with Tailwind CSS and Lucide Icons.
- 📱 **Fully Responsive**: Optimized for desktop and mobile devices.
- 📊 **Profile Management**: Easy-to-use student profile system.
- 🤖 **AI Ask Feature**: Integrated chatbot powered by Groq API (LLaMA 3.1) to assist students with academic and general questions.

---

## 🛠️ Tech Stack

### Frontend

- **React.js** – Dynamic, component-based UI
- **Tailwind CSS** – Utility-first styling
- **React Router** – Seamless navigation
- **Apollo Client** – GraphQL data management
- **lucide-react** – Elegant icons
- **react-parallax-tilt** – Interactive UI effects

### Backend

- **Node.js** & **Express.js** – Robust server framework
- **GraphQL** & **Apollo Server** – Flexible API queries
- **MongoDB (Mongoose)** – Scalable database
- **bcrypt** – Secure password hashing
- **Apollo upload client** & **cloudinary** – File uploads and storage
- **cors** – Cross-origin resource sharing

---

## 📷 Screenshots

| Homepage                                                                                                              | Student Dashboard                                                                                                          |
| --------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| ![Page]() | ![Dashboard]() |

---

## 🧠 AI Ask – Chat with Campus Bot

A conversational AI assistant built using **Groq API** and **LLaMA 3.1** model.

### 🔍 Capabilities

- Answer academic questions and general doubts
- Friendly chat-style UI
- Message history saved in session

You can access this feature on the `/askai` route.

---

## 🧑‍💻 Getting Started

### 🧪 Test Credentials

You can use the following test credentials to log in:

- **Email:** johndoe@gmail.com
- **Password:** John@123

### Prerequisites

- **Node.js** (v16 or higher)
- **npm** (v8 or higher)
- **MongoDB** (local or cloud instance)

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/p-thanks/My-Aurex.git
   ```

2. **Frontend Setup**

   ```bash
   cd My-Aurex/client
   npm install
   npm run dev
   ```

3. **Backend Setup**

   ```bash
   cd My-Aurex/server
   npm install
   ```

4. **Environment Variables**
   Create a `.env` file in the `server/` folder and add:

   ```env
   MONGO_URI=your_mongodb_connection_string
   CLOUDINARY_CLOUD_NAME=your_cloud_name
   CLOUDINARY_API_KEY=your_api_key
   CLOUDINARY_API_SECRET=your_api_secret

   PORT=5000
   ```

   Create a `.env` file in the `/client` folder and aa:

   ```env
   VITE_API_BASE_URL=http://localhost:5000
   VITE_GROQ_API_KEY=your_groq_api_key
   ```

5. **Run the Backend**
   ```bash
   node index.js
   ```

Open [http://localhost:5173](http://localhost:5173) to view the app in your browser.

---

## 🤝 Contributing

I welcome contributions! Follow these steps to contribute:

1. **Fork the Repository**
2. **Clone Your Fork**
   ```bash
   git clone https://github.com/p-thanks/My-Aurex.git
   ```
3. **Create a Branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```
4. **Make Changes** and **Commit**
   ```bash
   git commit -m "Add: your feature description"
   ```
5. **Push Changes**
   ```bash
   git push origin feature/your-feature-name
   ```
6. **Submit a Pull Request** on GitHub

Please read our [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines and check open [issues](https://github.com/p-thanks/My-Aurex/issues) for tasks.

---

## 📜 License

This project is licensed under the [Apache Licens 2.0](https://www.apache.org/licenses/LICENSE-2.0).

---

## 🙋‍♂️ Author

**Yogesh Rajak**  
Frontend Developer | React.js Enthusiast  
📧 [pthanksdev@gmail.com](mailto:pthanksdev@gmail.com)  
🌐 [Portfolio]()  
[![X]()
[![LinkedIn]()

---

## 🌟 Show Your Support

- ⭐ **Star this repo** to help others find it!
- 📢 Share MyCampus on [X]()
- 📢 Share on [LinkedIn]() or other platforms.

- 💬 Join the discussion in [GitHub Discussions](https://github.com/p-thanks/My-Aurex/discussions).

---
