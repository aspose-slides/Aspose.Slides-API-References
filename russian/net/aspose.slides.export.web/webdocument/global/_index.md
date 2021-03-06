---
title: Global
second_title: Справочник по API Aspose.Slides для .NET
description: Возвращает глобальное хранилище документа. Только для чтенияStorageaspose.slides.export.web/storage .
type: docs
weight: 20
url: /ru/net/aspose.slides.export.web/webdocument/global/
---
## WebDocument.Global property

Возвращает глобальное хранилище документа. Только для чтения[`Storage`](../../storage) .

```csharp
public Storage Global { get; }
```

### Примеры

Используя это`Global` имущество (реализация[`Storage`](../../storage) интерфейс) свойство a можно использовать позже в шаблоне:

```csharp
[C#]
var options = new WebDocumentOptions
{
    TemplateEngine = new RazorTemplateEngine(),
    OutputSaver = new FileOutputSaver(),
    EmbedImages = false
};

WebDocument document = new WebDocument(options);

// поместите свойство "slideMargin" для использования из шаблонов
document.Global.Put("slideMargin", 10);

// ... настроить другие параметры документа и затем сохранить документ
document.Save();
```

### Смотрите также

* class [Storage](../../storage)
* class [WebDocument](../../webdocument)
* пространство имен [Aspose.Slides.Export.Web](../../webdocument)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
