---
title: GetImage()
second_title: Aspose.Slides для C++ справочник API
description: "Возвращает миниатюру фигуры. По умолчанию используется тип границ миниатюры фигуры ShapeThumbnailBounds::Shape."
type: docs
weight: 651
url: /ru/aspose.slides/shape/getimage/
---
## Shape::GetImage() метод


Возвращает миниатюру фигуры. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) тип границ миниатюры фигуры используется по умолчанию.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage() override
```


### Возвращаемое значение

[Shape](../) миниатюра.

## Shape::GetImage(ShapeThumbnailBounds, float, float) метод


Возвращает миниатюру фигуры.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY) override
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../) тип границ миниатюры. |
| scaleX | **float** | масштаб X |
| scaleY | **float** | масштаб Y |

### Возвращаемое значение

[Shape](../) миниатюра или null в случае, когда [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) используется и у фигуры нет видимых элементов.

## Смотрите также

* Перечисление [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Тип-определение [SharedPtr](../../../system/sharedptr/)
* Класс [IImage](../../iimage/)
* Класс [Shape](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)