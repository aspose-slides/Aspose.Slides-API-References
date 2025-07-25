---
title: AddPicturePlaceholder
second_title: Aspose.Sildes для .NET API Справочник
description: Добавляет новую фигуру-заполнитель на макете слайда для удержания изображения.
type: docs
weight: 50
url: /ru/aspose.slides/layoutplaceholdermanager/addpictureplaceholder/
---

## LayoutPlaceholderManager.AddPicturePlaceholder метод

Добавляет новую фигуру-заполнитель на макете слайда для удержания изображения.

```csharp
public IAutoShape AddPicturePlaceholder(float x, float y, float width, float height)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | Single | Координата X новой фигуры-заполнителя. |
| y | Single | Координата Y новой фигуры-заполнителя. |
| width | Single | Ширина новой фигуры-заполнителя. |
| height | Single | Высота новой фигуры-заполнителя. |

### Значение Возврата

Созданный [`IAutoShape`](../../iautoshape) с заполнителем изображения.

### Примеры

Следующий пример показывает, как добавить фигуру-заполнитель изображения на макет слайда.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
	ILayoutSlide layout = pres.LayoutSlides.GetByType(SlideLayoutType.Blank);
	IAutoShape placeholder = layout.PlaceholderManager.AddPicturePlaceholder(20, 20, 200, 200);
}
```

### См. также

* интерфейс [IAutoShape](../../iautoshape)
* класс [LayoutPlaceholderManager](../../layoutplaceholdermanager)
* пространство имен [Aspose.Slides](../../layoutplaceholdermanager)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->