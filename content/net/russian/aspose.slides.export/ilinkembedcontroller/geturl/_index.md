---
title: GetUrl
second_title: Aspose.Sildes для .NET API Reference
description: Возвращает URL к внешнему объекту. Этот метод всегда вызывается, если GetObjectStoringLocation../getobjectstoringlocation вернул Link, и может быть вызван, если GetObjectStoringLocation../getobjectstoringlocation вернул Embed, но встраивание невозможно. Может быть вызван несколько раз для одного и того же идентификатора объекта.
type: docs
weight: 20
url: /ru/aspose.slides.export/ilinkembedcontroller/geturl/
---

## ILinkEmbedController.GetUrl метод

Возвращает URL к внешнему объекту. Этот метод всегда вызывается, если [`GetObjectStoringLocation`](../getobjectstoringlocation) вернул Link, и может быть вызван, если [`GetObjectStoringLocation`](../getobjectstoringlocation) вернул Embed, но встраивание невозможно. Может быть вызван несколько раз для одного и того же идентификатора объекта.

```csharp
public string GetUrl(int id, int referrer)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| id | Int32 | Идентификатор объекта. Этот идентификатор сохраняется как уникальный для всей операции. |
| referrer | Int32 | идентификатор ссылающегося объекта или 0, если объект ссылается на корневой документ. Может быть использован для генерации относительной ссылки. |

### Возвращаемое значение

URL внешнего объекта или null, если этот объект должен быть проигнорирован.

### См. также

* интерфейс [ILinkEmbedController](../../ilinkembedcontroller)
* пространство имен [Aspose.Slides.Export](../../ilinkembedcontroller)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->