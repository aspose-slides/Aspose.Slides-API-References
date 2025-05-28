---
title: DetectTables
second_title: Справочник по API Aspose.Sildes для .NET
description: Определяет, обнаруживать ли таблицы при импорте PDF-файла.
type: docs
weight: 20
url: /ru/aspose.slides.import/pdfimportoptions/detecttables/
---

## Свойство PdfImportOptions.DetectTables

Определяет, обнаруживать ли таблицы при импорте PDF-файла.

```csharp
public bool DetectTables { get; set; }
```

### Примеры

Пример:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    using (Stream stream = new FileStream("document.pdf", FileMode.Open, FileAccess.Read, FileShare.Read))
    {
        // установить обнаружение таблиц
        pres.Slides.AddFromPdf(stream, new PdfImportOptions { DetectTables = true });
    }
    
    pres.Save("fromPdfDocument.pptx", SaveFormat.Pptx);
}
```

### Смотрите также

* класс [PdfImportOptions](../../pdfimportoptions)
* пространство имен [Aspose.Slides.Import](../../pdfimportoptions)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->