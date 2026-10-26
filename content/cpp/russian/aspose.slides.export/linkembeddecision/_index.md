---
title: LinkEmbedDecision
second_title: Aspose.Slides для C++ — справочник API
description: Определяет, как объект будет обрабатываться при сохранении.
type: docs
weight: 911
url: /ru/aspose.slides.export/linkembeddecision/
---
## LinkEmbedDecision enum

Определяет, как объект будет обрабатываться при сохранении.

```cpp
enum class LinkEmbedDecision
```

### Значения

| Name | Value | Description |
| --- | --- | --- |
| Link | 0 | Объект будет храниться внешне, ссылка будет указана через URL |
| Embed | 1 | Объект должен быть встроен в генерируемый файл, если это возможно. Если встраивание невозможно, будет вызван GetUrl и, в зависимости от результата, объект будет ссылаться по URL или будет проигнорирован. |
| Ignore | 2 | Объект будет проигнорирован. |

## См. также

* Пространство имён [Aspose::Slides::Export](../)
* Библиотека [Aspose.Slides](../../)