# vitrinaflorista.com — статическая версия сайта

Сайт перенесён с GPT Sites и не требует сервера: это обычные HTML-файлы.

## Что где лежит
- `index.html` — страница покупателя (перенесена без изменений)
- `florist.html` — новая страница для флориста
- `img/florist/` — иллюстрации для страницы флориста. Чтобы поставить реальное фото, положите файл с тем же именем
  (или поменяйте путь в `florist.html`). Рекомендуемые пропорции: 01 — 4:5, 02 — 1:1, katalog-* — 1:1,
  04 — вертикаль 2:3, 06 — 4:3, 07 и 08 — 1:1, 09 — 5:4, 10 и 11 — 4:5.
- `o-vitrina-florista`, `kak-rabotaet`, `dlya-florista`, `zakazy-v-telegram`, `foto-soglasovanie-buketa`,
  `qr-dlya-florista`, `status-zakaza` — SEO-страницы (перенесены без изменений)
- `legal`, `privacy`, `terms` — юридические страницы (без изменений)
- `CNAME` — домен для GitHub Pages; `sitemap.xml`, `robots.txt` — для поисковиков

## Публикация на GitHub Pages
1. Создайте публичный репозиторий и загрузите в него всё содержимое этой папки (Add file → Upload files).
2. Settings → Pages → Source: Deploy from a branch, ветка `main`, папка `/ (root)`.
3. Custom domain: `vitrinaflorista.com`, затем включите Enforce HTTPS.
4. У регистратора домена: A-записи `@` → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153;
   CNAME `www` → `<ваш-логин>.github.io`.

## Публикация на Beget
Загрузите содержимое папки в `public_html`. Файл `.htaccess` уже настроен, чтобы адреса работали без `.html`.
