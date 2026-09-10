<h1 align="center">
  <img src="logo.svg#gh-light-mode-only" width="40" height="40" alt="" valign="middle" />
  <img src="logo-white.svg#gh-dark-mode-only" width="40" height="40" alt="" valign="middle" />
  Smalum
</h1>
<p align="center"><strong>Small language. Sharp diagrams.</strong></p>
<p align="center">
  <a href="https://smalum.ru">Сайт</a> ·
  <a href="https://app.smalum.ru">Редактор</a> ·
  <a href="https://docs.smalum.ru">Документация</a>
</p>

**Smalum** — редактор диаграмм как код.

PlantUML, Mermaid, BPMN, DFD и SQL остаются исходником. Вид, который вы довели на холсте, записывается обратно в тот же файл как **оверлей**: служебные комментарии вида `' SM:` / `// SM:` / `%% SM:` с координатами блоков и линий. При следующем разборе состав схемы снова берётся из текста, а картинка — из оверлея, поэтому раскладка не сгорает и уезжает вместе с файлом в git.

Развиваем **Web IDE** для диаграмм как код: тот же исходник, что в git и в markdown, открывается, правится и доводится до сдачи.

<p align="center">
  <a href="https://app.smalum.ru"><img src="og-image.png" alt="Smalum — редактор диаграмм как код" width="640"></a>
</p>

## Зачем

Пишете схему текстом — как в репозитории. На холсте готовите картинку к ревью, ТЗ или слайду. Следующая правка исходника не откатывает раскладку: оверлей остаётся в файле.

## Для кого

Системные аналитики, архитекторы, разработчики и технические писатели, которым схема — сдача, а не одноразовая иллюстрация.

## Этот GitHub

Публичные плагины. Редактор — веб-приложение: **[app.smalum.ru](https://app.smalum.ru)**.

### VS Code / Cursor

Пока нет в Marketplace. Скачайте `.vsix` с [релизов](https://github.com/smalum/vscode/releases) и установите: Extensions → `…` → **Install from VSIX…**.

```bash
code --install-extension smalum-vscode-0.1.0.vsix
cursor --install-extension smalum-vscode-0.1.0.vsix
```

Репозиторий: [github.com/smalum/vscode](https://github.com/smalum/vscode)

### Obsidian

Пока нет в Community Plugins.

1. Установите [BRAT](https://github.com/TfTHacker/obsidian42-brat).
2. Add a beta plugin → `https://github.com/smalum/obsidian`

Либо скачайте `main.js`, `manifest.json`, `styles.css` с [релизов](https://github.com/smalum/obsidian/releases) и положите в `.obsidian/plugins/smalum/`.

Репозиторий: [github.com/smalum/obsidian](https://github.com/smalum/obsidian)

## English

Smalum is a diagrams-as-code editor for PlantUML, Mermaid, BPMN, DFD and SQL. The picture you arrange on the canvas is written back into the file as an **overlay** — `SM:` comments with coordinates next to the source. The next parse keeps the structure from the text and the layout from the overlay, so the diagram travels with git. We are building a Web IDE around that source.

[smalum.ru](https://smalum.ru) · [app](https://app.smalum.ru) · [docs](https://docs.smalum.ru)

---

[dev@smalum.ru](mailto:dev@smalum.ru)
