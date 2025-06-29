CommerceWebApi.zip : .net core webApi include SQLite (instead of sql server), unzip and build it.
my-MOD-front.zip : react front, unzip it and then npm install and npm start
order-service.zip : nodejs Api,unzip it and then npm run dev
Note: you must have installed mongodb  

רכיבים מרכזיים :Azure Static Web Apps / Azure Storage (Static Website Hosting) + Azure CDN: לאירוח אפליקציית ה-React (Frontend).Azure App Service: לאירוח ה-Node.js API (Backend).Azure Cosmos DB (MongoDB API): לבסיס הנתונים NoSQL (לדוגמה: מוצרים, קטגוריות, סלי קניות).Azure SQL Database / Azure SQL Managed Instance: לבסיס הנתונים Relational (לדוגמה: פרטי משתמשים, היסטוריית הזמנות, נתוני לוגיסטיקה, נתונים אנליטיים).Azure DevOps: לפיתוח, בקרת גרסאות, CI/CD, ניהול פרויקטים וניהול תצורה.Azure Monitor + Application Insights: לניטור, לוגינג וטריסינג.  שילוב שני בסיסי הנתונים (SQL Relational + NoSQL Document) עם יכולות ה-DevOps והאבטחה של Azure מאפשר לנו ליהנות מהיתרונות של כל אחד מהם, תוך בניית מערכת גמישה, סקיילבילית ומאובטחת. חשוב לתכנן בקפידה את הפיצול בין הנתונים: איזה סוג נתונים הולך לאן, ומהו המודל הטוב ביותר עבור כל קבוצת נתונים.  
