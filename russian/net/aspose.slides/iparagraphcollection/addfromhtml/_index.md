---
title: AddFromHtml
second_title: Справочник по API Aspose.Slides для .NET
description: Добавляет в коллекцию текст из указанной строки html.
type: docs
weight: 60
url: /ru/net/aspose.slides/iparagraphcollection/addfromhtml/
---
## AddFromHtml(string) {#addfromhtml}

Добавляет в коллекцию текст из указанной строки html.

```csharp
public void AddFromHtml(string text)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | String | Текст HTML. |

### Смотрите также

* interface [IParagraphCollection](../../iparagraphcollection)
* пространство имен [Aspose.Slides](../../iparagraphcollection)
* сборка [Aspose.Slides](../../../)

---

## AddFromHtml(string, IExternalResourceResolver, string) {#addfromhtml_1}

Добавляет в коллекцию текст из указанной строки html.

```csharp
public void AddFromHtml(string text, IExternalResourceResolver resolver, string uri)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | String | Текст HTML. |
| resolver | IExternalResourceResolver | Объект обратного вызова Resolver, который разрешает URI и извлекает объекты, на которые ссылаются. |
| uri | String | URI для добавления документа HTML. Используется для разрешения относительных ссылок. |

### Примечания

Указание резолвера потенциально может привести к уязвимости. Используйте с осторожностью.

### Смотрите также

* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* interface [IParagraphCollection](../../iparagraphcollection)
* пространство имен [Aspose.Slides](../../iparagraphcollection)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->