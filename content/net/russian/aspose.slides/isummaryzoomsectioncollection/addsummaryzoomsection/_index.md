---
title: AddSummaryZoomSection
second_title: Справочник по API Aspose.Slides для .NET
description: Создает новый объект Сводная секция масштабирования и добавляет его в коллекцию
type: docs
weight: 20
url: /ru/aspose.slides/isummaryzoomsectioncollection/addsummaryzoomsection/
---
## ISummaryZoomSectionCollection.AddSummaryZoomSection method

Создает новый объект Сводная секция масштабирования и добавляет его в коллекцию

```csharp
public ISummaryZoomSection AddSummaryZoomSection(ISection section)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| section | ISection | Section для нового элемента Summary Zoom Section[`ISection`](../../isection) |

### Возвращаемое значение

Добавлен[`ISummaryZoomFrame`](../../isummaryzoomframe)element

### Примечания

Если элемент для этого раздела уже существует в коллекции, возвращается существующий элемент.

### Примеры

Пример демонстрирует получение элемента Summary Zoom Section по индексу:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame) pres.Slides[1].Shapes[0];
    ISummaryZoomSectionCollection collection = zoomFrame.SummaryZoomCollection;
    ISummaryZoomSection newZoomSection = collection.AddSummaryZoomSection(pres.Sections[3]);
}
```

### Смотрите также

* interface [ISummaryZoomSection](../../isummaryzoomsection)
* interface [ISection](../../isection)
* interface [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection)
* пространство имен [Aspose.Slides](../../isummaryzoomsectioncollection)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
