# Vortex Store — каталог

Отсюда приложение Vortex Store в Vortex OS берёт список приложений.

- `index.json` — каталог (название, версия, размер, SHA-256, ссылка на APK).
- `icons/` — иконки.
- Сами APK лежат в релизе [apks](https://github.com/wwwmnl119-eng/vortex-store/releases/tag/apks).

Магазин ставит приложение, только если SHA-256 и имя пакета совпадают с каталогом.
