---
title: GetImage()
second_title: Aspose.Slides для C++: справочник API
description: "Возвращает миниатюру фигуры. ShapeThumbnailBounds::Shape тип границ миниатюры фигуры используется по умолчанию."
type: docs
weight: 547
url: /ru/aspose.slides/ishape/getimage/
---
## IShape::GetImage() метод


Возвращает миниатюру фигуры. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) тип границ миниатюры фигуры используется по умолчанию.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage()=0
```


### Возвращаемое значение

[Shape](../../shape/) миниатюра.

## IShape::GetImage(ShapeThumbnailBounds, float, float) метод


Возвращает миниатюру фигуры.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../../shape/) тип границ миниатюры. |
| scaleX | **float** | масштаб по X |
| scaleY | **float** | масштаб по Y |

### Возвращаемое значение

[Shape](../../shape/) миниатюра или null в случае, когда [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) используется и у фигуры нет видимых элементов.

## См. также

* Перечисление [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IImage](../../iimage/)
* Класс [IShape](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)