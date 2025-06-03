---
title: Description
second_title: Справочник по API Aspose.Slides для .NET
description: Возвращает текстовое описание объекта раздела Презентация Зум.
type: docs
weight: 20
url: /ru/aspose.slides/isummaryzoomsection/description/
---

## Свойство ISummaryZoomSection.Description

Возвращает текстовое описание объекта раздела Презентация Зум.

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
    zoomSection.Description = "Описание";
}
```

### См. также

* интерфейс [ISummaryZoomSection](../../isummaryzoomsection)
* пространство имен [Aspose.Slides](../../isummaryzoomsection)
* сборка [Aspose.Slides](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для Aspose.Slides.dll -->
