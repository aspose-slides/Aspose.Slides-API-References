---
title: Add()
second_title: Справочник API Aspose.Slides для C++
description: Добавляет значения ширины и высоты указанного объекта SizeF к значениям координат X и Y указанного объекта PointF соответственно.
type: docs
weight: 144
url: /ru/system.drawing/pointf/add/
---
## PointF::Add(const PointF\&, const SizeF\&) method


Добавляет значения ширины и высоты указанного объекта [SizeF](../../sizef/) к значениям координат X и Y указанного объекта [PointF](../) соответственно.

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const SizeF &size)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| point | const [PointF](../)\& | Точка для перемещения |
| size | const [SizeF](../../sizef/)\& | Объект [SizeF](../../sizef/), определяющий значения, добавляемые к координатам **point** |

### Возвращаемое значение

Новый объект [PointF](../), у которого значение координаты X равно сумме значения координаты X **point** и значения ширины **size**, а значение координаты Y равно сумме значения координаты Y **point** и значения высоты **size**.

## PointF::Add(const PointF\&, const Size\&) method


Добавляет значения ширины и высоты указанного объекта [Size](../../size/) к значениям координат X и Y указанного объекта [PointF](../) соответственно.

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const Size &size)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| point | const [PointF](../)\& | Точка для перемещения |
| size | const [Size](../../size/)\& | Объект [Size](../../size/), определяющий значения, добавляемые к координатам **point** |

### Возвращаемое значение

Новый объект [PointF](../), у которого значение координаты X равно сумме значения координаты X **point** и значения ширины **size**, а значение координаты Y равно сумме значения координаты Y **point** и значения высоты **size**.

## См. также

* Класс [PointF](../)
* Класс [SizeF](../../sizef/)
* Класс [Size](../../size/)
* Пространство имён [System::Drawing](../../)
* Библиотека [Aspose.Slides](../../../)