# PlaytonOS 0.1 Alpha

Браузерная виртуальная ОС от Playton Corporation. Откройте index.html или опубликуйте корень репозитория через GitHub Pages.

## Приложения

Магазин устанавливает встроенные приложения, а также пакеты `.papp` (JSON). Пример: `{"name":"Моё приложение","icon":"🚀","html":"<h1>Привет!</h1>"}`. Сторонние приложения запускаются в изолированном iframe. Данные сохраняются в localStorage текущего браузера; это не настоящий диск и не облачная синхронизация.

## GitHub Pages

Settings → Pages → Deploy from a branch → main / (root) → Save.
