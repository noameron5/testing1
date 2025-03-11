# Spring Boot Demo

פרויקט Spring Boot בסיסי לניהול הודעות. נבנה כחלק מהתנסות ב-GitHub.

## דרישות טכניות

- Java 21
- Maven 3.8.0+
- MySQL 8.0+
- Apache Tomcat 10.0+ (מובנה בתוך Spring Boot)

## התקנה והגדרה

1. העתק את המאגר: `git clone https://github.com/YOUR_USERNAME/spring-boot-demo.git`
2. כנס לתיקיית הפרויקט: `cd spring-boot-demo`
3. עדכן את הגדרות מסד הנתונים ב-`src/main/resources/application.properties`
4. הרץ את הפרויקט: `mvn spring-boot:run`

## API Endpoints

- `GET /api/messages` - קבלת כל ההודעות
- `GET /api/messages/{id}` - קבלת הודעה לפי מזהה
- `POST /api/messages` - יצירת הודעה חדשה
- `PUT /api/messages/{id}` - עדכון הודעה קיימת
- `DELETE /api/messages/{id}` - מחיקת הודעה
