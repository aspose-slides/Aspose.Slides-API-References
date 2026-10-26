---
title: Rectangle class
second_title: Aspose.Slides для Python через .NET справочник API
description: Хранит набор из четырёх целых чисел, представляющих расположение и размер прямоугольника.
type: docs
url: /ru/aspose.slides/rectangle/
net_type: System.Drawing.Rectangle
---
## Rectangle класс

Хранит набор из четырёх целых чисел, представляющих расположение и размер прямоугольника. Совместим с .NET `System.Drawing.Rectangle`.

Тип Rectangle предоставляет следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self, x=0, y=0, width=0, height=0)`](/slides/python-net/ru/aspose.slides/rectangle/__init__/#int-int-int-int) | Создаёт прямоугольник с указанным расположением и размером. Значения с плавающей запятой усекаются до целых чисел. |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`x`](/slides/python-net/ru/aspose.slides/rectangle/x/) | Возвращает координату x верхнего левого угла этого прямоугольника.<br/>            Только для чтения **int**. |
| [`y`](/slides/python-net/ru/aspose.slides/rectangle/y/) | Возвращает координату y верхнего левого угла этого прямоугольника.<br/>            Только для чтения **int**. |
| [`width`](/slides/python-net/ru/aspose.slides/rectangle/width/) | Возвращает ширину этого прямоугольника.<br/>            Только для чтения **int**. |
| [`height`](/slides/python-net/ru/aspose.slides/rectangle/height/) | Возвращает высоту этого прямоугольника.<br/>            Только для чтения **int**. |
| [`left`](/slides/python-net/ru/aspose.slides/rectangle/left/) | Возвращает координату x левой границы этого прямоугольника. Equals to `x`.<br/>            Только для чтения **int**. |
| [`top`](/slides/python-net/ru/aspose.slides/rectangle/top/) | Возвращает координату y верхней границы этого прямоугольника. Equals to `y`.<br/>            Только для чтения **int**. |
| [`right`](/slides/python-net/ru/aspose.slides/rectangle/right/) | Возвращает координату x, которая является суммой `x` и `width` этого прямоугольника.<br/>            Только для чтения **int**. |
| [`bottom`](/slides/python-net/ru/aspose.slides/rectangle/bottom/) | Возвращает координату y, которая является суммой `y` и `height` этого прямоугольника.<br/>            Только для чтения **int**. |
| [`is_empty`](/slides/python-net/ru/aspose.slides/rectangle/is_empty/) | Определяет, равны ли все числовые свойства этого прямоугольника нулю.<br/>            Только для чтения **bool**. |

## Методы

| Метод | Описание |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/ru/aspose.slides/rectangle/contains/#int-int) | Определяет, находится ли указанная точка внутри этого прямоугольника. |
| [`contains(self, point)`](/slides/python-net/ru/aspose.slides/rectangle/contains/#point) | Определяет, находится ли указанная точка внутри этого прямоугольника. |
| [`contains(self, rect)`](/slides/python-net/ru/aspose.slides/rectangle/contains/#rectangle) | Определяет, полностью ли прямоугольная область, представленная `rect`, содержится в этом прямоугольнике. |


### Примечания

Прямоугольники сравниваются по своему расположению и размеру с помощью `==` и могут использоваться в качестве ключей словарей или элементов множеств.


### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)