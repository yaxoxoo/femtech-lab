# FemTech Lab — лендинг (один файл)

Весь сайт — это **один самодостаточный файл `index.html`**: HTML + CSS (в `<style>`) + JS и данные (в `<script>`). Никаких внешних файлов и сборок.

## Открыть
- Двойной клик по `index.html` (откроется в браузере), или
- сервер: `python3 -m http.server 4611` → `http://localhost:4611/`

## Что редактировать (всё внутри `index.html`, в нижнем `<script>`)
- **Alumni** — массив `window.ALUMNI` (32 шт). Объект: `n`=имя, `c`=компания, `co`=страна, `t`=категория, `d`=описание, `p`=URL фото. Добавить — допиши объект.
- **Отзывы** — массив `window.TESTIMONIALS` (16 шт). Объект: `n`=имя, `r`=роль, `q`=цитата, `p`=URL фото.
- **FAQ / тексты / ссылки** — прямо в разметке секций.

## Картинки
Фото подставляются по URL; пусто → аккуратная серая плашка (без «битых картинок»).
- Отзывы — фото уже проставлены (с femtechlab.com), кроме Polly Thomson.
- Alumni — впиши URL в поле `p` нужного человека.
- Остальное (hero, галерея, benefits-визуал, лого backers/featured, photo-секция) — плейсхолдеры `REPLACE_*` в разметке, замени на свои ссылки.

## Ссылки (кнопки)
Проставлены: Invest / Become an Investment Partner → Syndicate; Book a Call → Corporate; Join the Waitlist → Waitlist; Events → Luma.
Осталось: `AIRTABLE_APPLY` (Apply to join ×3), `AIRTABLE_REGISTER` (навбар), и форма баннера → Mailchimp (`MAILCHIMP_ACTION_URL`).

## Интерактив
Слайдеры (галерея, alumni, отзывы — стрелки), бегущая строка логотипов, аккордеон FAQ, newsletter-баннер (выезжает справа-снизу при каждой загрузке).
