---
title: Global
second_title: Справочник по API Aspose.Slides для .NET
description: Возвращает глобальное хранилище документа. Только для чтенияStorageaspose.slides.export.web/storage.
type: docs
weight: 20
url: /ru/net/aspose.slides.export.web/webdocument/global/
---
## WebDocument.Global property

Возвращает глобальное хранилище документа. Только для чтения[`Storage`](../../storage).

```csharp
public Storage Global { get; }
```

### Примеры

Используя это свойство`Global`(реализация[`Storage`](../../storage)interface) свойство может быть использовано позже в шаблоне:

```csharp
[C#]
var options = new WebDocumentOptions
{
    TemplateEngine = new RazorTemplateEngine(),
    OutputSaver = new FileOutputSaver(),
    EmbedImages = false
};

WebDocument document = new WebDocument(options);

 // поместите свойство "slideMargin" для использования из templates
document.Global.Put("slideMargin", 10);

 // ... настраиваем другие параметры документа и затем сохраняем document
document.Save();
```

### Смотрите также

* class [Storage](../../storage)
* class [WebDocument](../../webdocument)
* пространство имен [Aspose.Slides.Export.Web](../../webdocument)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->