---
title: LinkEmbedDecision
second_title: Справочник по API Aspose.Slides для .NET
description: Определяет как будет обрабатываться объект при сохранении.
type: docs
weight: 3880
url: /ru/net/aspose.slides.export/linkembeddecision/
---
## LinkEmbedDecision enumeration

Определяет, как будет обрабатываться объект при сохранении.

```csharp
public enum LinkEmbedDecision
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| Link | `0` | Объект будет храниться во внешнем хранилище, на который ссылается URL |
| Embed | `1` | Объект должен быть встроен в сгенерированный файл, если это возможно. Если встраивание невозможно, будет вызван GetUrl и, в зависимости от результата, объект будет сослан по URL или проигнорирован. |
| Ignore | `2` | Объект будет проигнорирован. |

### Смотрите также

* пространство имен [Aspose.Slides.Export](../../aspose.slides.export)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->