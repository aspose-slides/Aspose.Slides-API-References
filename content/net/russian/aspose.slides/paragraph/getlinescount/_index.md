---
title: GetLinesCount
second_title: Aspose.Sildes для .NET API Справочник
description: Получить количество строк в абзаце.
type: docs
weight: 60
url: /ru/aspose.slides/paragraph/getlinescount/
---

## Метод Paragraph.GetLinesCount

Получить количество строк в абзаце.

```csharp
public int GetLinesCount()
```

### Возвращаемое значение

Количество строк в абзаце

### Примеры

Пример:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide sld = pres.Slides[0];
    IAutoShape ashp = sld.Shapes.AddAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
    IParagraph para = ashp.TextFrame.Paragraphs[0];
    IPortion portion = para.Portions[0];
    portion.Text = "Aspose Paragraph GetLinesCount() Example";
    Console.WriteLine("Lines Count = {0}", para.GetLinesCount());
}
```

### См. также

* класс [Paragraph](../../paragraph)
* пространство имен [Aspose.Slides](../../paragraph)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->