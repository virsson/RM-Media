# RM-Media

Публичные изображения для статей РМ-ГРУПП. Репозиторий используется как источник
картинок по прямым ссылкам: файлы доступны через CDN и вставляются в статьи без
локальной загрузки.

## Структура

```
articles/<slug>/<file>.jpg
```

`slug` совпадает со слагом статьи в таблицах `blog` / `blog2`. Один ключ/тема —
один набор изображений на все площадки и адаптации.

## Публичная ссылка

```
https://cdn.jsdelivr.net/gh/virsson/RM-Media@main/articles/<slug>/<file>.jpg
```

Для статьи `rm-150-applikator-etiketok` префикс:
`https://cdn.jsdelivr.net/gh/virsson/RM-Media@main/articles/rm-150-applikator-etiketok/`

Альтернатива (raw): `https://raw.githubusercontent.com/virsson/RM-Media/main/articles/<slug>/<file>.jpg`.

## Правила

- Имена файлов — латиницей, kebab-case, без пробелов.
- Оптимизировать перед загрузкой (WebP/JPEG по возможности, без лишнего веса).
- В `alt` писать конкретно, что изображено: модель, узел, исполнение.
- Удалять файлы только когда на них нет ссылок в опубликованных статьях.
