---
title: LinkEmbedDecision
second_title: Aspose.Slides для Android через справочник Java API
description: Определяет, как объект будет обрабатываться при сохранении.
type: docs
url: /ru/com.aspose.slides/linkembeddecision/
---
**Наследование:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

Определяет, как объект будет обрабатываться при сохранении.
## Поля

| Поле | Описание |
| --- | --- |
| [Link](#Link) | Объект будет храниться внешне, ссылка будет по URL |
| [Embed](#Embed) | Объект должен быть встроен в сгенерированный файл, если это возможно. |
| [Ignore](#Ignore) | Объект будет проигнорирован. |
### Ссылка {#Link}
```
public static final int Link
```

Объект будет храниться внешне, ссылка будет по URL

### Встраивание {#Embed}
```
public static final int Embed
```

Объект должен быть встроен в сгенерированный файл, если это возможно. Если встраивание невозможно, будет вызван метод GetUrl и, в зависимости от результата, объект будет ссылаться по URL или будет проигнорирован.

### Игнорировать {#Ignore}
```
public static final int Ignore
```

Объект будет проигнорирован.