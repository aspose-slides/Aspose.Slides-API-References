---
title: Clone()
second_title: Справочник API Aspose.Slides для C++
description: Создает копию текущего объекта.
type: docs
weight: 183
url: /ru/system.drawing/bitmap/clone/
---
## Bitmap::Clone() метод


Создает копию текущего объекта.

```cpp
virtual SharedPtr<Image> System::Drawing::Bitmap::Clone() override
```


### Возвращаемое значение

Копия текущего объекта.

## Bitmap::Clone(Rectangle, Imaging::PixelFormat) метод


Создает объект [Bitmap](../), который представляет копию области растрового изображения, представленного текущим объектом.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(Rectangle rect, Imaging::PixelFormat format)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | Прямоугольник, определяющий область для копирования |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Формат пикселей для нового [Bitmap](../) |

### Возвращаемое значение

Созданный объект [Bitmap](../)

## Bitmap::Clone(RectangleF, Imaging::PixelFormat) метод


Создает объект [Bitmap](../), который представляет копию области растрового изображения, представленного текущим объектом.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(RectangleF rect, Imaging::PixelFormat format)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | Прямоугольник, определяющий область для копирования |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Формат пикселей для нового [Bitmap](../) |

### Возвращаемое значение

Созданный объект [Bitmap](../)

## См. также

* Перечисление [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [Image](../../image/)
* Класс [Bitmap](../)
* Класс [Rectangle](../../rectangle/)
* Класс [RectangleF](../../rectanglef/)
* Пространство имён [System::Drawing](../../)
* Библиотека [Aspose.Slides](../../../)