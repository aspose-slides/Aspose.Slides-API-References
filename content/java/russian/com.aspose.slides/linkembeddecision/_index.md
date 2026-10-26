---
title: LinkEmbedDecision
second_title: Aspose.Slides для Java справочник API
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
| [Link](#Link) | Объект будет храниться внешне, ссылка на него будет по URL |
| [Embed](#Embed) | По возможности объект должен быть встроен в генерируемый файл. |
| [Ignore](#Ignore) | Объект будет игнорироваться. |
### Ссылка {#Link}
```
public static final int Link
```


Объект будет храниться внешне, ссылка на него будет по URL

### Встроить {#Embed}
```
public static final int Embed
```


По возможности объект должен быть встроен в генерируемый файл. Если встраивание невозможно, будет вызван GetUrl и, в зависимости от результата, объект будет ссылаться по URL или будет игнорироваться.

### Игнорировать {#Ignore}
```
public static final int Ignore
```


Объект будет игнорироваться.