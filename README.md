# Vijayalaxmi Biradar

Java Full Stack Developer 

---

## About

MCA graduate (2025) from BLDEA's V.P. Dr. P.G. Halakatti College of Engineering & Technology, Vijayapura with a CGPA of 8.3. I specialize in building secure, scalable full-stack applications using Java, Spring Boot, and React.js, with hands-on experience in Spring Security, Spring Data JPA, Hibernate, REST APIs, and Microservices architecture.
I've built and deployed production-ready projects including a JWT-secured Online Examination Portal with real-time anti-cheat proctoring, an AI Email Reply Generator on AWS Elastic Beanstalk, and a Weather Forecast App containerized with Docker and deployed on Render. I'm skilled in database design with MySQL and PostgreSQL, and comfortable with tools like Kafka, Docker, Maven, Git, and CI/CD pipelines.

Currently seeking entry-level Java Full Stack development opportunities where I can contribute to real-world systems and grow alongside a strong engineering team.

---

## Technical Skills

**Programming Languages:** Java (8/11/17+), SQL, JavaScript (ES6+)

**Frameworks and Technologies:** Spring Boot, Spring MVC, Spring Security (JWT), Spring Data JPA, Spring Cloud, Hibernate, Swagger/OpenAPI, React.js

**Web Technologies:** HTML5, CSS3

**Databases:** MySQL, PostgreSQL

**Cloud and DevOps Tools:** AWS (Elastic Beanstalk, RDS), Docker, Maven, CICD GitHub ACtions

**Version Control and Testing:** Git, GitHub, JUnit 5, Mockito, Postman, Swagger/OpenAPI

**Architecture and Design:** Microservices, MVC Design Pattern, Role-Based Access Control (RBAC), Layered Architecture, REST API Design, Computer Networks

**Tools:** IntelliJ IDEA, Eclipse IDE, VS Code, MySQL Workbench

## Projects

### 🛡️ SecureExam Portal
[github.com/vijayalaxmi168/secureexam-portal](https://github.com/vijayalaxmi168/secureexam-portal)

A full-stack online examination portal built with Java 21 and Spring Boot 3.4, where security is enforced at every layer. Students take timed exams under real-time proctoring — correct answers are protected using DTO projection so they never appear in any API response. Tab switches are detected in the browser, recorded in a dedicated audit table, and after 3 violations the exam is automatically force-terminated at the Spring service layer — not just JavaScript.  Scoring happens entirely server-side by comparing submitted answers against database values, making score manipulation impossible from the client.

**Stack:** Java 21 · Spring Boot 3.4 · Spring Security 6 · JWT · Refresh Token Rotation · Spring Data JPA · MySQL · React  · Axios · Swagger UI

---

### 🚨 Disaster Response Platform
[github.com/vijayalaxmi168/disaster-response-platform](https://github.com/vijayalaxmi168/disaster-response-platform)

A microservices-based disaster response coordination system built with Java 21 and Spring Boot 3.2, where six independently deployable services communicate through service discovery and REST. Citizens raise rescue requests in real time, volunteers self-assign and get matched via OpenFeign inter-service calls, and rescued people are placed into shelters with live capacity tracking. Every state change — assignment, shelter placement, completion — triggers an automated notification, keeping citizens and volunteers informed at each step without manual intervention. All services register with Eureka for dynamic discovery and route through a single Spring Cloud Gateway entry point, so the architecture scales the way a real production system would.

Stack: Java 17 · Spring Boot 3.2 · Spring Cloud Gateway · Netflix Eureka · OpenFeign · Spring Data JPA · PostgreSQL · React 18 · Vite · Axios · Swagger UI

### AI Email Reply Generator
[github.com/vijayalaxmi168/ai-email-reply-generator](https://github.com/vijayalaxmi168/ai-email-reply-generator)

A Spring Boot backend integrated with Google Gemini AI to generate 
context-aware email replies based on email content and selected tone. 
Exposes REST APIs consumed by a Thymeleaf web UI, enabling AI-powered 
reply generation with persistent history tracking on AWS cloud.

Deployed on AWS Elastic Beanstalk with RDS MySQL for production-grade 
cloud deployment with environment-based configuration.

🌐 Live — [ai-email-reply-generator](http://ai-email-reply-generator-env.eba-h28mqqps.ap-south-1.elasticbeanstalk.com/)

**Stack:** Spring Boot · Google Gemini AI · REST API · Spring Data JPA · 
Hibernate · MySQL · AWS Elastic Beanstalk · AWS RDS · 
Thymeleaf · Maven · Lombok

---
## WeatherPulse Forecast App
[github.com/vijayalaxmi168/Weather-Forecast](https://github.com/vijayalaxmi168/Weather-Forecast)

A production-deployed full-stack weather forecast application built with **Spring Boot 3**, consuming the OpenWeatherMap REST API via **RestTemplate** and mapping JSON responses to clean Java DTOs using **Jackson**. Displays real-time 5-day forecast grouped by day with temperature, humidity, wind speed and weather icons via **Thymeleaf** templating.Containerized with **Docker** and deployed live on **Render** with a cron-job configured for uptime monitoring.

🌐 Live — [weatherpulse-forecast.onrender.com](https://weatherpulse-forecast.onrender.com/)

**Stack:** Spring Boot 3 · Thymeleaf · RestTemplate · Jackson · Lombok · Docker · Render · Maven

---
### Portfolio Website
[vijayalaxmi06-portfolio](https://vijayalaxmi06-portfolio.netlify.app/)

Personal portfolio site showcasing projects, technical skills, and services. Built with HTML, CSS, Javascript and deployed on Netlify.

**Stack:** HTML · CSS3 · Javascript

---

## Education

**Master of Computer Applications (MCA)**
at BLDEA's V.P. Dr. P.G. Halakatti College of Engineering & Technology, Vijayapura
2025 · CGPA: 8.3

**Bachelor of Computer Applications (BCA)**
at SB Arts And KCP Science College, Vijayapura
2023 . CGPA: 8.2


---

## Contact

- **Portfolio:** [vijayalaxmi06-portfolio](https://vijayalaxmi06-portfolio.netlify.app/)
- **LinkedIn:** [linkedin.com/in/vijaylaxmi-biradar-v24](https://www.linkedin.com/in/vijaylaxmi-biradar-v24/)
- **Email:** [vijayalaxmib0106@gmail.com](mailto:vijayalaxmib0106@gmail.com)
- **GitHub:** [github.com/vijayalaxmi168](https://github.com/vijayalaxmi168)
