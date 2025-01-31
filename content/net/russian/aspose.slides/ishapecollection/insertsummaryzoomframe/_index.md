---
title: InsertSummaryZoomFrame
second_title: Справочник по API Aspose.Slides для .NET
description: Создает новый объект Суммарный масштаб и вставляет его в коллекцию по указанному индексу.
type: docs
weight: 330
url: /ru/aspose.slides/ishapecollection/insertsummaryzoomframe/
---
## IShapeCollection.InsertSummaryZoomFrame method

Создает новый объект Суммарный масштаб и вставляет его в коллекцию по указанному индексу.

```csharp
public ISummaryZoomFrame InsertSummaryZoomFrame(int index, float x, float y, float width, 
    float height)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Нулевой на основе индекса, в который следует вставить рамку масштабирования раздела. |
| x | Single | Координата X нового кадра увеличения сеченияSingle. |
| y | Single | Координата Y нового кадра увеличения сеченияSingle. |
| width | Single | Ширина нового кадра масштабирования разделаSingle. |
| height | Single | Высота нового кадра масштабирования разделаSingle. |

### Возвращаемое значение

Создан объект сводного масштабирования[`ISummaryZoomFrame`](../../isummaryzoomframe).

### Исключения

| исключение | условие |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | В презентации нет разделов, или целевой слайд не принадлежит ни к одному из разделов. |

### Примечания

Этот метод создает новый Суммарный масштаб и помещает в него коллекцию объектов для всех разделов в эта презентация.

### Примеры

В этом примере демонстрируется создание и вставка объекта Summary Zoom по указанному индексу коллекции (предположим, что в презентации "Presentation.pptx" не менее двух разделов):

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    ISummaryZoomFrame zoomFrame = pres.Slides[0].Shapes.InsertSummaryZoomFrame(2, 150, 20, 50, 50);
}
```

### Смотрите также

* interface [ISummaryZoomFrame](../../isummaryzoomframe)
* interface [IShapeCollection](../../ishapecollection)
* пространство имен [Aspose.Slides](../../ishapecollection)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
