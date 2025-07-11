---
title: Size
second_title: Aspose.Sildes для .NET API Справочник
description: Получает или устанавливает размер кисти для линии в пунктах.
type: docs
weight: 20
url: /ru/aspose.slides.ink/inkbrush/size/
---

## Свойство InkBrush.Size

Получает или устанавливает размер кисти для линии в пунктах.

```csharp
public SizeF Size { get; set; }
```

### Примеры

Пример:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    IInk ink = (IInk)pres.Slides[0].Shapes[0];
    IInkTrace[] traces = ink.Traces;
    IInkBrush brush = traces[0].Brush;
    SizeF brushSize = brush.Size;
    brush.Size = new SizeF(5f, 10f);
}
```

### См. также

* класс [InkBrush](../../inkbrush)
* пространство имен [Aspose.Slides.Ink](../../inkbrush)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->