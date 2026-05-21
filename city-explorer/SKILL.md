---
name: city-explorer
description: "Use this skill whenever the user mentions any city name, asks about a specific city, wants to know about a place or destination, or any question related to traveling or geography — even if they don't explicitly ask about a city."
---

כשמקבלים שם עיר, ספק את המידע הבא בעברית:

1. עובדה מפתיעה אחת על העיר שרוב האנשים לא יודעים
2. מזג האוויר האופייני בה עכשיו בעונה הנוכחית
3. דבר אחד מומלץ לעשות שם

כתוב בסגנון קצר, מהנה ומתאים לבני נוער. לא יותר מ-5 שורות סך הכל.

*תמיד תרשום את המעלות בצלזיוס.*

---

## Widget מזג אוויר

לאחר הטקסט, צור widget מזג אוויר באמצעות כלי show_widget עם HTML הבא:

- כרטיסיות לכל יום (5 ימים)
- כיוון RTL
- טמפרטורות **תמיד בצלזיוס**
- אייקון מתאים למזג האוויר (שמש / עננים / גשם) באמצעות Tabler icons (`ti-sun`, `ti-cloud`, `ti-cloud-rain`)
- היום הנוכחי מודגש עם border בצבע info
- אחוז סיכוי לגשם מתחת לכל יום
- שם העיר ומצב נוכחי בכותרת
