---
title: Output
second_title: Справочник по API Aspose.Slides для .NET
description: Возвращает набор выходных элементов документа. Только чтениеOutputaspose.slides.export.web/webdocument/output.
type: docs
weight: 40
url: /ru/net/aspose.slides.export.web/webdocument/output/
---
## WebDocument.Output property

Возвращает набор выходных элементов документа. Только чтение`Output`.

```csharp
public Output Output { get; }
```

### Примеры

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    var options = new WebDocumentOptions
    {
        TemplateEngine = new RazorTemplateEngine(),
        OutputSaver = new FileOutputSaver(),
        EmbedImages = false
    };
    
    WebDocument document = new WebDocument(options);

     // добавить «index.html» в выходные файлы, используя шаблон «index» для его создания и переменную pre как model
    document.Output.Add("index.html", "index", pres);

     // ... настраиваем другие параметры документа и затем сохраняем document
    document.Save();
}
```

### Смотрите также

* class [Output](../../output)
* class [WebDocument](../../webdocument)
* пространство имен [Aspose.Slides.Export.Web](../../webdocument)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->