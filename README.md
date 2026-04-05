# UKSOFT Landing Page

Оновлена збірка без JS-перемикання всього контенту.
Кожна мова має окрему статичну сторінку, тому головна і privacy більше не змішуються.

## Основні URL
- Українська головна: `/`
- English home: `/en/`
- Deutsch home: `/de/`
- Polski home: `/pl/`
- Русский home: `/ru/`
- Türkçe home: `/tr/`

## Privacy URL
- English default privacy: `/privacy/`
- Українська: `/privacy/uk/`
- Deutsch: `/privacy/de/`
- Polski: `/privacy/pl/`
- Русский: `/privacy/ru/`
- Türkçe: `/privacy/tr/`

## Важливо
Маршрут виду `/privacy.html/en` для статичного GitHub Pages ненадійний.
Використано сумісний формат через папки: `/privacy/`, `/privacy/uk/`, `/privacy/de/` тощо.

## Файли
- `index.html`
- `styles.css`
- папки мов: `en/`, `de/`, `pl/`, `ru/`, `tr/`
- папка `privacy/`
- `privacy.html` — редирект на `/privacy/`
- `assets/icon.webp`
