# Dual Calendar | تقویم دوگانه

Gregorian and Shamsi (Jalali) month calendars, side by side, in a single HTML file.
تقویم میلادی و شمسی در یک صفحه، کنار هم، فقط با یک فایل HTML.

## Features | ویژگی‌ها

- **Two calendars at once:** Gregorian (Monday-first) and Shamsi (Saturday-first, with Thursday and Friday as the weekend), each with its own month navigation.
- **Layout toggle:** switch between side-by-side and stacked views.
- **Today highlight** in both calendars, plus a "Today" button to jump back.
- **Bilingual date header:** today's date written in full in Persian and English, with the Turkish month name shown too.
- **Turkish public holidays** are marked on the Gregorian calendar: fixed national days, plus Ramazan and Kurban Bayramı (including arefe) for 2024–2028.
- **Persian digits and month names** on the Shamsi side.
- **Installable (PWA):** includes a web app manifest and icons.
- No build step, no framework, no dependencies. Date conversion is done in the file itself (jalaali-js style algorithm).

## Usage | نحوهٔ استفاده

Open `index.html` in a modern browser, or host the folder on GitHub Pages.

Keep these next to `index.html` so the icons and install support work:

```
index.html
manifest.json
icons/
  favicon-16.png
  favicon-32.png
  apple-touch-icon.png
  logo-inline.png
```

Fonts (Fraunces, Inter, Vazirmatn) load from Google Fonts, so the first load needs an internet connection.

## Notes | نکات

- Religious holidays are listed per year. After 2028 only the fixed national holidays are marked, so add the new dates to `TR_HOLIDAYS_RELIGIOUS` in the script.
- Official Iranian holidays are not marked on the Shamsi calendar.

## Author

Motasem Sadeghi

## License

[MIT](LICENSE)
