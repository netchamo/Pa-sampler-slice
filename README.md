# חותך הדגימות · Pa Sample Slicer

כלי דפדפן שהופך הקלטה רציפה של נגן לסט דגימות מוכן לייבוא ל-KORG Pa4X ולמקלדות דומות.

## מה הוא עושה
- **חיתוך אוטומטי** של הקלטה ארוכה לתווים בודדים, עם pre-roll ופייד.
- **זיהוי גובה** ושיוך כל קטע לתו ולשכבת ולוסיטי. אפשר לפי סדר ההקלטה, לפי גובה שזוהה, או במצב תופים.
- **נרמול עוצמה בין שכבות** לפי המכה ולא רק לפי השיא, כך שהמעבר מחלש לחזק נשאר אמין.
- **פריסטים** לפסנתר, באס, גיטרה, נשיפה ובראס, תופים, וסינת' ופדים.
- **מקלדת נגינה** לבדיקת הסט הממופה. אפשר לחבר מקלדת שליטה ב-USB (Web MIDI, בכרום ובאדג').
- **ייצוא ZIP**: קובצי WAV מסודרים לפי שכבה, `mapping.csv` עם טווחי קלידים וולוסיטי, ו-README עם שלבי הבנייה בכלי.

## שימוש
פותחים את `index.html` בדפדפן, או את כתובת GitHub Pages של הפרויקט. אין צורך בשרת ואין התקנה. כל העיבוד נעשה במכשיר, ושום קובץ לא נשלח החוצה.

## שמות התווים
C4 = הדו האמצעי = MIDI 60, כמו בכלים של KORG.

---

A single-file browser tool that slices a continuous instrument recording into velocity-layered multisamples for the KORG Pa4X. It handles slicing, pitch detection, inter-layer level matching, a playable preview keyboard with Web MIDI input, and ZIP export with a mapping CSV. Everything runs locally in the browser.
