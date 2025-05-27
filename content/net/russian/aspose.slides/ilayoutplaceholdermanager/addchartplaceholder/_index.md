---
title: AddChartPlaceholder
second_title: Aspose.Slides для .NET API Справочник
description: Добавляет новую фигуру-заполнитель на слайд компоновки для размещения графика.
type: docs
weight: 10
url: /ru/aspose.slides/ilayoutplaceholdermanager/addchartplaceholder/
---

## ILayoutPlaceholderManager.AddChartPlaceholder метод

Добавляет новую фигуру-заполнитель на слайд компоновки для размещения графика.

```csharp
public IAutoShape AddChartPlaceholder(float x, float y, float width, float height)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | Single | X-координата новой фигуры-заполнителя. |
| y | Single | Y-координата новой фигуры-заполнителя. |
| width | Single | Ширина новой фигуры-заполнителя. |
| height | Single | Высота новой фигуры-заполнителя. |

### Возвращаемое значение

Созданный [`IAutoShape`](../../iautoshape) с заполнителем графика.

### Примеры

Следующий пример показывает, как добавить фигуру-заполнитель графика на слайд компоновки.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
	ILayoutSlide layout = pres.LayoutSlides.GetByType(SlideLayoutType.Blank);
	IAutoShape placeholder = layout.PlaceholderManager.AddChartPlaceholder(20, 20, 200, 200);
}
```

### См. также

* интерфейс [IAutoShape](../../iautoshape)
* интерфейс [ILayoutPlaceholderManager](../../ilayoutplaceholdermanager)
* пространство имен [Aspose.Slides](../../ilayoutplaceholdermanager)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано с помощью xmldocmd для Aspose.Slides.dll -->