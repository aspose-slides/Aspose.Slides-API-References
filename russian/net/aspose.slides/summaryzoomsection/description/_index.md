---
title: Description
second_title: Справочник по API Aspose.Slides для .NET
description: Возвращает текстовое описание объекта Суммарный раздел масштабирования.
type: docs
weight: 10
url: /ru/net/aspose.slides/summaryzoomsection/description/
---
## SummaryZoomSection.Description property

Возвращает текстовое описание объекта Суммарный раздел масштабирования.

```csharp
public string Description { get; set; }
```

### Примеры

Пример:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomSection zoomSection = zoomFrame.SummaryZoomCollection[1];
    zoomSection.Description = "Description";
}
```

### Смотрите также

* class [SummaryZoomSection](../../summaryzoomsection)
* пространство имен [Aspose.Slides](../../summaryzoomsection)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->