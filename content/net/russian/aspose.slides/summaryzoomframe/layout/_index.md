---
title: Layout
second_title: Справочник по API Aspose.Slides для .NET
description: Получает расположение разделов сводного масштабирования в кадре. Значение по умолчанию  GridLayout.
type: docs
weight: 10
url: /ru/aspose.slides/summaryzoomframe/layout/
---
## SummaryZoomFrame.Layout property

Получает расположение разделов сводного масштабирования в кадре. Значение по умолчанию — GridLayout.

```csharp
public ZoomLayout Layout { get; }
```

### Примеры

Пример демонстрирует получение элемента Summary Zoom Section по индексу:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomFrame zoomFrame = pres.Slides[1].Shapes[0] as ISummaryZoomFrame;
    ZoomLayout layout = zoomFrame.Layout;
}
```

### Смотрите также

* enum [ZoomLayout](../../zoomlayout)
* class [SummaryZoomFrame](../../summaryzoomframe)
* пространство имен [Aspose.Slides](../../summaryzoomframe)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
