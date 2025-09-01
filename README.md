# Content Lab — static site

Готовый многостраничный сайт (HTML/CSS, офлайн-совместимый).

## Структура
- `index.html` — главная
- `services.html` — услуги
- `funnels.html` — связки
- `price.html` — прайс
- `contact.html` — контакты
- `styles.css` — общий стиль
- `.nojekyll` — отключение Jekyll на GitHub Pages

## Быстрый запуск на GitHub Pages (через Actions)
1. Создайте пустой репозиторий на GitHub (например, `content-lab-site`), **Public**.
2. Скачайте этот архив и распакуйте.
3. Загрузите все файлы в корень репозитория через GitHub (Upload files).
4. Перейдите в Settings → Pages → выберите **GitHub Actions** и ничего не меняйте — workflow уже добавлен.
5. После первого пуша и успешного билда получите ссылку вида `https://<username>.github.io/content-lab-site/`.

## Запуск через ветку main (без Actions)
1. Зайдите в Settings → Pages → Build and deployment.
2. В Source выберите **Deploy from a branch**.
3. Branch: `main`, folder: `/ (root)`.
4. `Save` — страница станет доступна по тому же адресу.

## Локальный предпросмотр
Просто откройте `index.html` двойным кликом — сайт работает офлайн.

## Контакты
- Telegram: https://t.me/warpof
