---
title: Rectangle()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт новый экземпляр объекта Rectangle, представляющего прямоугольник с координатами X и Y и значениями ширины и высоты, установленными в 0.
type: docs
weight: 1
url: /ru/system.drawing/rectangle/rectangle/
---
## Rectangle::Rectangle() конструктор

Создаёт новый экземпляр объекта [Rectangle](../), представляющий прямоугольник с координатами X и Y и значениями ширины и высоты, установленными в 0.

```cpp
System::Drawing::Rectangle::Rectangle()
```

## Rectangle::Rectangle(int, int, int, int) конструктор

Создаёт новый экземпляр объекта [Rectangle](../), представляющего прямоугольник с указанными координатами его верхнего левого угла и шириной и высотой.

```cpp
System::Drawing::Rectangle::Rectangle(int x, int y, int width, int height)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Значение координаты X верхнего левого угла прямоугольника |
| y | int | Значение координаты Y верхнего левого угла прямоугольника |
| width | int | Ширина прямоугольника |
| height | int | Высота прямоугольника |

## Rectangle::Rectangle(const Point\&, const Size\&) конструктор

Создаёт новый экземпляр объекта [Rectangle](../), представляющего прямоугольник, координаты его верхнего левого угла задаются экземпляром класса [Point](../../point/), а его ширина и высота — экземпляром класса [Size](../../size/).

```cpp
System::Drawing::Rectangle::Rectangle(const Point &location, const Size &size)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| location | const [Point](../../point/)\& | Указывает расположение верхнего левого угла прямоугольника |
| size | const [Size](../../size/)\& | Указывает ширину и высоту прямоугольника |

## Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_\&) конструктор

Создаёт новый экземпляр объекта [Rectangle](../), представляющего прямоугольник, эквивалентный указанному.

```cpp
System::Drawing::Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_ &rect)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | const **System::Windows::Forms::Screen::Rectangle_**\& | Экземпляр класса **System::Windows::Forms::Screen::Rectangle_**, указывающий положение и размер прямоугольника, который будет представлен создаваемым объектом |

## Смотрите также

* Класс [Rectangle](../)
* Класс [Point](../../point/)
* Класс [Size](../../size/)
* Пространство имён [System::Drawing](../../)
* Библиотека [Aspose.Slides](../../../)