---
title: InsertSummaryZoomFrame
second_title: Aspose.Slides для .NET API Reference
description: Создает новый объект Summary Zoom и вставляет его в коллекцию по указанному индексу.
type: docs
weight: 380
url: /ru/aspose.slides/shapecollection/insertsummaryzoomframe/
---

## ShapeCollection.InsertSummaryZoomFrame method

Создает новый объект Summary Zoom и вставляет его в коллекцию по указанному индексу.

```csharp
public ISummaryZoomFrame InsertSummaryZoomFrame(int index, float x, float y, float width, 
    float height)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Индекс с нуля, по которому должен быть вставлен Section Zoom frame. |
| x | Single | Координата X нового Section Zoom frame Single. |
| y | Single | Координата Y нового Section Zoom frame Single. |
| width | Single | Ширина нового Section Zoom frame Single. |
| height | Single | Высота нового Section Zoom frame Single. |

### Возвращаемое значение

Созданный объект Summary Zoom [`ISummaryZoomFrame`](../../isummaryzoomframe).

### Исключения

| исключение | условие |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | В презентации нет секций или целевой слайд не принадлежит никакой секции. |

### Заметки

Этот метод создает новый Summary Zoom и помещает в него коллекцию объектов для всех секций в этой презентации.

### Примеры

Этот пример демонстрирует создание и вставку объекта Summary Zoom по указанному индексу в коллекции (предположим, что в презентации "Presentation.pptx" есть как минимум две секции):

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    ISummaryZoomFrame zoomFrame = pres.Slides[0].Shapes.InsertSummaryZoomFrame(2, 150, 20, 50, 50);
}
```

### См. также

* интерфейс [ISummaryZoomFrame](../../isummaryzoomframe)
* класс [ShapeCollection](../../shapecollection)
* пространство имен [Aspose.Slides](../../shapecollection)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->