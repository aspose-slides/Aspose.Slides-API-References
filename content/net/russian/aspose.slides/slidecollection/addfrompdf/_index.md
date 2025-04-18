---
title: AddFromPdf
second_title: Справочник по API Aspose.Slides для .NET
description: Создает слайды из документа PDF и добавляет их в конец коллекции.
type: docs
weight: 80
url: /ru/aspose.slides/slidecollection/addfrompdf/
---
## AddFromPdf(string) {#addfrompdf_1}

Создает слайды из документа PDF и добавляет их в конец коллекции.

```csharp
public ISlide[] AddFromPdf(string path)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Путь к документу PDF |

### Возвращаемое значение

Добавлены слайды

### Примеры

Пример:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    pres.Slides.AddFromPdf("document.pdf");
    pres.Save("fromPdfDocument.pptx", SaveFormat.Pptx);
}
```

### Смотрите также

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* пространство имен [Aspose.Slides](../../slidecollection)
* сборка [Aspose.Slides](../../../)

---

## AddFromPdf(Stream) {#addfrompdf}

Создает слайды из документа PDF и добавляет их в конец коллекции.

```csharp
public ISlide[] AddFromPdf(Stream pdfStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdfStream | Stream | Поток, который будет использоваться как источник PDF-документа |

### Возвращаемое значение

Добавлены слайды

### Примеры

Пример:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    using (Stream stream = new FileStream("document.pdf", FileMode.Open, FileAccess.Read, FileShare.Read))
    {
        pres.Slides.AddFromPdf(stream);
    }
    
    pres.Save("fromPdfDocument.pptx", SaveFormat.Pptx);
}
```

### Смотрите также

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* пространство имен [Aspose.Slides](../../slidecollection)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
