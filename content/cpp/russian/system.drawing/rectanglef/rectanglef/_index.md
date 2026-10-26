---
title: RectangleF()
second_title: Aspose.Slides для C++ справка по API
description: Создаёт новый экземпляр объекта RectangleF, представляющего прямоугольник с координатами X и Y и значениями ширины и высоты, установленными в 0.
type: docs
weight: 1
url: /ru/system.drawing/rectanglef/rectanglef/
---
## RectangleF::RectangleF() конструктор

Constructs a new instance of [RectangleF](../) object that represents a rectangle with X and Y coordinates and width and hegiht values set to 0.

```cpp
System::Drawing::RectangleF::RectangleF()
```

## RectangleF::RectangleF(float, float, float, float) конструктор

Constructs a new instance of [RectangleF](../) object that represents a rectangle with the specified coordinates of its upper left corner and width and height.

```cpp
System::Drawing::RectangleF::RectangleF(float x, float y, float width, float height)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Значение координаты X верхнего левого угла прямоугольника |
| y | **float** | Значение координаты Y верхнего левого угла прямоугольника |
| width | **float** | Ширина прямоугольника |
| height | **float** | Высота прямоугольника |

## RectangleF::RectangleF(const PointF\&, const SizeF\&) конструктор

Constructs a new instance of [RectangleF](../) object that represents a rectangle with the coordinates of its upper left corner specified as an instance of [PointF](../../pointf/) class and its width and height as an instance of [SizeF](../../sizef/) class.

```cpp
System::Drawing::RectangleF::RectangleF(const PointF &location, const SizeF &size)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| location | const [PointF](../../pointf/)\& | Указывает местоположение верхнего левого угла прямоугольника |
| size | const [SizeF](../../sizef/)\& | Указывает ширину и высоту прямоугольника |

## RectangleF::RectangleF(const Rectangle\&) конструктор

Constructs a new instance of [RectangleF](../) object that represents the rectangle equivalent to the specified one.

```cpp
System::Drawing::RectangleF::RectangleF(const Rectangle &rect)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Экземпляр класса [Rectangle](../../rectangle/), который задаёт положение и размер прямоугольника, представляемого создаваемым объектом |

## См. также

* Класс [RectangleF](../)
* Класс [PointF](../../pointf/)
* Класс [SizeF](../../sizef/)
* Класс [Rectangle](../../rectangle/)
* Пространство имён [System::Drawing](../../)
* Библиотека [Aspose.Slides](../../../)