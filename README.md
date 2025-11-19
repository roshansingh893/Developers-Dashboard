# 🚀 Developers Dashboard – Backend  
A Spring Boot–based backend for tracking developer productivity, commit analytics, GitHub activity, and repository insights.

---

## 📌 Features  
- 🔐 **Auth & JWT Security**  
- 🧩 **Modular Spring Boot Architecture**  
- 📊 **Developer Commit Insights & GitHub GraphQL Integration**  
- 🐳 **Docker Support**  
- ⚙️ **Maven-Based Build System**

---

## 📁 Project Structure  

```
Developer-Productivity-Analytics-Backend
│
├── .mvn/
├── docker/
├── src/
│   ├── main/
│   └── test/
│
├── mvnw
├── mvnw.cmd
├── pom.xml
└── README.md
```

---

## 🛠️ Tech Stack  
- **Java 17+**  
- **Spring Boot**  
- **Spring Security (JWT)**  
- **GitHub GraphQL API**  
- **Docker**  
- **Maven**

---

## ⚙️ Running the Project  

### **1️⃣ Install Dependencies**
```
mvn clean install
```

### **2️⃣ Run the Application**
```
mvn spring-boot:run
```

### **3️⃣ Build JAR**
```
mvn package
```

### **4️⃣ Run with Docker**
```
docker build -t developers-dashboard-backend .
docker run -p 8080:8080 developers-dashboard-backend
```

---

## 🔐 Authentication  
JWT-based authentication flow  
- Login → Generate token  
- Token used for secure endpoints  
- Refresh token support (if applicable)

---

## 🧠 API Overview (High Level)
- `/auth/login` – Authenticate user  
- `/github/user` – Fetch GitHub profile  
- `/github/stats` – Fetch commit insights  
- `/health` – Service Health Check  

---

## 📄 License  
This project belongs to **Roshan Singh**.  
All rights reserved.

---

## 🤝 Contributing  
Currently private development. PRs not open.

