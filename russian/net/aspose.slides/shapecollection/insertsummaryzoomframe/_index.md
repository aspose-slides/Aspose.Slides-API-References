---
title: InsertSummaryZoomFrame
second_title: Справочник по API Aspose.Slides для .NET
description: Создает новый объект Summary Zoom и вставляет его в коллекцию по указанному индексу.
type: docs
weight: 380
url: /ru/net/aspose.slides/shapecollection/insertsummaryzoomframe/
---
## ShapeCollection.InsertSummaryZoomFrame method

Создает новый объект Summary Zoom и вставляет его в коллекцию по указанному индексу.

```csharp
public ISummaryZoomFrame InsertSummaryZoomFrame(int index, float x, float y, float width, 
    float height)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Отсчитываемый от нуля индекс, по которому должна быть вставлена рамка масштабирования раздела. |
| x | Single | Координата X нового кадра увеличения сеченияSingle. |
| y | Single | Координата Y нового кадра увеличения сеченияSingle. |
| width | Single | Ширина новой рамки масштабирования разделаSingle. |
| height | Single | Высота нового кадра масштабирования разделаSingle. |

### Возвращаемое значение

Создан объект Суммарное масштабирование[`ISummaryZoomFrame`](../../isummaryzoomframe).

### Исключения

| исключение | условие |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | В презентации нет разделов, или целевой слайд не принадлежит ни к одному из разделов. |

### Примечания

Этот метод создает новое сводное масштабирование и помещает в него набор объектов для всех разделов этой презентации.

### Примеры

В этом примере показано создание и вставка объекта Summary Zoom по указанному индексу коллекции (предположим, что в презентации «Presentation.pptx» есть как минимум два раздела):

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    ISummaryZoomFrame zoomFrame = pres.Slides[0].Shapes.InsertSummaryZoomFrame(2, 150, 20, 50, 50);
}
```

### Смотрите также

* interface [ISummaryZoomFrame](../../isummaryzoomframe)
* class [ShapeCollection](../../shapecollection)
* пространство имен [Aspose.Slides](../../shapecollection)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
