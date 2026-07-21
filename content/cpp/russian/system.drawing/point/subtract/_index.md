---
title: Subtract()
second_title: Aspose.Slides для C++ справочник API
description: Вычитает значения ширины и высоты указанного объекта Size из значений координат X и Y указанного объекта Point соответственно.
type: docs
weight: 196
url: /ru/system.drawing/point/subtract/
---
## Point::Subtract(const Point\&, const Size\&) метод

Вычитает значения ширины и высоты указанного [Size](../../size/) объекта из значений координат X и Y указанного [Point](../) объекта соответственно.

```cpp
static Point System::Drawing::Point::Subtract(const Point &point, const Size &size)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| point | const [Point](../)\& | Точка для перемещения |
| size | const [Size](../../size/)\& | Объект [Size](../../size/), который задает значения, вычитаемые из значений координат **point** |

### Возвращаемое значение

Новый объект [Point](../), у которого значение координаты X равно результату вычитания значения ширины **size** из значения координаты X **point**, а значение координаты Y равно результату вычитания значения высоты **size** из значения координаты Y **point**.

## См. также

* Класс [Point](../)
* Класс [Size](../../size/)
* Пространство имён [System::Drawing](../../)
* Библиотека [Aspose.Slides](../../../)