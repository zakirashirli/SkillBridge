# 🚀 SkillBridge

SkillBridge is a **Spring Boot–based platform** that connects people who need specific skills with freelancers, mentors, and professionals who can provide them.  
The goal is to **bridge the gap** between talent and demand — simple, scalable, and efficient.

---

## ✨ Features

- 🔐 **User Authentication** (Register/Login with JWT)
- 👤 **Profile Management** (bio, skills, experience)
- 🔍 **Skill Search** (find mentors/freelancers by keyword)
- 📅 **Booking System** (request & schedule sessions/gigs)
- ⭐ **Feedback & Ratings** (after completion)
- 🔔 **Notifications** (for requests and updates)

**Future Enhancements:**
- 💳 Payment Integration (Stripe/PayPal)
- 🤖 AI-based skill matching
- 📱 Mobile app (React Native / Flutter)

---

## 🛠️ Tech Stack

- **Backend:** Java 17, Spring Boot, Spring Data JPA, Spring Security  
- **Database:** PostgreSQL (or MySQL)  
- **Frontend (optional MVP):** React / Angular  
- **DevOps (later):** Docker, AWS (EC2, RDS), GitHub Actions  
- **Build Tool:** Maven or Gradle  
- **Other Tools:** Postman (API testing), IntelliJ IDEA  

---

## 🏗️ System Design

### User Roles
- **Client** → Posts requests & books freelancers  
- **Freelancer** → Offers skills & accepts jobs  
- **Admin** → Manages users, reports, platform health  

### Flow Example
1. Client searches for a skill (`"Java Interview Prep"`)  
2. Freelancers with matching skills are notified  
3. Client books a session → Freelancer accepts  
4. Session completed → Client leaves feedback  

---

## ⚙️ Installation & Setup

```bash
# Clone the repo
git clone https://github.com/yourusername/skillbridge.git
cd skillbridge

# Build the project
mvn clean install

# Run the app
mvn spring-boot:run
