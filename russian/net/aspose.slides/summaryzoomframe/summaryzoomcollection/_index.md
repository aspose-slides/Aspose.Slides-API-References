---
title: SummaryZoomCollection
second_title: Справочник по API Aspose.Slides для .NET
description: ПолучаетISummaryZoomSectionCollectionaspose.slides/isummaryzoomsectioncollectionдля объекта Сводная рамка масштабирования.
type: docs
weight: 20
url: /ru/net/aspose.slides/summaryzoomframe/summaryzoomcollection/
---
## SummaryZoomFrame.SummaryZoomCollection property

Получает[`ISummaryZoomSectionCollection`](../../isummaryzoomsectioncollection)для объекта Сводная рамка масштабирования.

```csharp
public ISummaryZoomSectionCollection SummaryZoomCollection { get; }
```

### Примеры

Пример демонстрирует получение элемента Summary Zoom Section по индексу:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomFrame zoomFrame = pres.Slides[1].Shapes[0] as ISummaryZoomFrame;
    ISummaryZoomSectionCollection collection = zoomFrame.SummaryZoomCollection;
}
```

### Смотрите также

* interface [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection)
* class [SummaryZoomFrame](../../summaryzoomframe)
* пространство имен [Aspose.Slides](../../summaryzoomframe)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->