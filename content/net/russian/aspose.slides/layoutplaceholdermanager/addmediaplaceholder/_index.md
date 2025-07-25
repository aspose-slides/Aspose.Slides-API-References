---
title: AddMediaPlaceholder
second_title: Aspose.Slides для .NET API Справочник
description: Добавляет новую фигуру-заполнитель на слайде макета для хранения медиаобъекта.
type: docs
weight: 30
url: /ru/aspose.slides/layoutplaceholdermanager/addmediaplaceholder/
---

## LayoutPlaceholderManager.AddMediaPlaceholder метод

Добавляет новую фигуру-заполнитель на слайде макета для хранения медиаобъекта.

```csharp
public IAutoShape AddMediaPlaceholder(float x, float y, float width, float height)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | Single | Координата X новой фигуры-заполнителя. |
| y | Single | Координата Y новой фигуры-заполнителя. |
| width | Single | Ширина новой фигуры-заполнителя. |
| height | Single | Высота новой фигуры-заполнителя. |

### Возвращаемое значение

Созданный [`IAutoShape`](../../iautoshape) с медиа-заполнителем.

### Примеры

Следующий пример показывает, как добавить фигуру-заполнитель медиа на слайд макета.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
	ILayoutSlide layout = pres.LayoutSlides.GetByType(SlideLayoutType.Blank);
	IAutoShape placeholder = layout.PlaceholderManager.AddMediaPlaceholder(20, 20, 200, 200);
}
```

### См. также

* интерфейс [IAutoShape](../../iautoshape)
* класс [LayoutPlaceholderManager](../../layoutplaceholdermanager)
* пространство имен [Aspose.Slides](../../layoutplaceholdermanager)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->