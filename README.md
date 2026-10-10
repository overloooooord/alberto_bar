# Alberto bar · пиво к закускам

Мини-меню бара Alberto (Алматы, ул. Гоголя 144): к каждому сету закусок подобрано пиво из карты бара, с описанием вкуса и пирамидой нот.

Сделано командой Flavor Tree.

## Как открыть

Это статический сайт без сборки: `index.html`, данные в `pilot/`, фото в `img/`.

- Vercel: импортировать репозиторий, Framework Preset = Other, без команд сборки.
- GitHub Pages: Settings → Pages → Deploy from branch → `main` / root.
- Локально: `python3 -m http.server 8091` и открыть http://127.0.0.1:8091/

Меню сначала берётся из API Flavor Tree; если API не ответил, страница показывает снимок из `pilot/alberto-menu.json`.
