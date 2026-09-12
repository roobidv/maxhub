# MAXHUB

אתר נחיתה סטטי בעברית (RTL) המציג את פתרונות MAXHUB:

- מסכי מגע חכמים לכיתות לימוד
- מערכת וידאו קונפרנס
- מערכת שיתוף תוכן אלחוטית

## מבנה הפרויקט

```
MAXHUB/
├── index.html      # דף הבית
├── style.css       # עיצוב האתר
├── images/         # תמונות הסקשנים
└── videos/         # קבצי וידאו מקומיים (אופציונלי)
```

## צפייה מקומית

פתחו את `index.html` בדפדפן, או הריצו שרת מקומי:

```powershell
python -m http.server 8000
```

וגלשו אל `http://localhost:8000`

## העלאה ל-GitHub Pages

1. צרו repository חדש ב-GitHub
2. דחפו את הקוד:

```powershell
git remote add origin https://github.com/USERNAME/REPO.git
git push -u origin main
```

3. בהגדרות ה-repo: **Settings → Pages → Source: main branch**
4. האתר יהיה זמין בכתובת `https://USERNAME.github.io/REPO/`
