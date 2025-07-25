---
title: AddMediaPlaceholder
second_title: Aspose.Sildes для .NET API Reference
description: Добавляет новую форму-заполнитель на слайд макета для хранения медиа-объекта.
type: docs
weight: 30
url: /ru/aspose.slides/ilayoutplaceholdermanager/addmediaplaceholder/
---

## ILayoutPlaceholderManager.AddMediaPlaceholder метод

Добавляет новую форму-заполнитель на слайд макета для хранения медиа-объекта.

```csharp
public IAutoShape AddMediaPlaceholder(float x, float y, float width, float height)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | Single | X-координата новой формы-заполнителя. |
| y | Single | Y-координата новой формы-заполнителя. |
| width | Single | Ширина новой формы-заполнителя. |
| height | Single | Высота новой формы-заполнителя. |

### Возвращаемое значение

Созданный [`IAutoShape`](../../iautoshape) с медиа-заполнителем.

### Примеры

Следующий пример показывает, как добавить форму-заполнитель медиа на слайд макета.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
	ILayoutSlide layout = pres.LayoutSlides.GetByType(SlideLayoutType.Blank);
	IAutoShape placeholder = layout.PlaceholderManager.AddMediaPlaceholder(20, 20, 200, 200);
}
```

### См. также

* interface [IAutoShape](../../iautoshape)
* interface [ILayoutPlaceholderManager](../../ilayoutplaceholdermanager)
* namespace [Aspose.Slides](../../ilayoutplaceholdermanager)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->