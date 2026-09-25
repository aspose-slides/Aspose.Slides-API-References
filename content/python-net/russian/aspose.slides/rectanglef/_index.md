---
title: RectangleF class
second_title: Aspose.Slides для Python через .NET API
description: Содержит набор из четырёх чисел с плавающей запятой, представляющих местоположение и размер прямоугольника.
type: docs
url: /ru/aspose.slides/rectanglef/
net_type: System.Drawing.RectangleF
---
## RectangleF класс

Содержит набор из четырёх чисел с плавающей запятой, представляющих местоположение и размер прямоугольника. Совместим с .NET `System.Drawing.RectangleF`.

**Наследование:**[`RectangleF`](/slides/python-net/ru/aspose.slides/rectanglef) → [`Rectangle`](/slides/python-net/ru/aspose.slides/rectangle)

Тип RectangleF предоставляет следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self, x=0.0, y=0.0, width=0.0, height=0.0)`](/slides/python-net/ru/aspose.slides/rectanglef/__init__/#float-float-float-float) | Создает прямоугольник с указанным местоположением и размером. |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`x`](/slides/python-net/ru/aspose.slides/rectanglef/x/) | Получает координату x верхнего левого угла этого прямоугольника.<br/>            Только для чтения **float**. |
| [`y`](/slides/python-net/ru/aspose.slides/rectanglef/y/) | Получает координату y верхнего левого угла этого прямоугольника.<br/>            Только для чтения **float**. |
| [`width`](/slides/python-net/ru/aspose.slides/rectanglef/width/) | Получает ширину этого прямоугольника.<br/>            Только для чтения **float**. |
| [`height`](/slides/python-net/ru/aspose.slides/rectanglef/height/) | Получает высоту этого прямоугольника.<br/>            Только для чтения **float**. |
| [`left`](/slides/python-net/ru/aspose.slides/rectanglef/left/) | Получает координату x левого края этого прямоугольника. Равно `x`.<br/>            Только для чтения **float**. |
| [`top`](/slides/python-net/ru/aspose.slides/rectanglef/top/) | Получает координату y верхнего края этого прямоугольника. Равно `y`.<br/>            Только для чтения **float**. |
| [`right`](/slides/python-net/ru/aspose.slides/rectanglef/right/) | Получает координату x, равную сумме `x` и `width` этого прямоугольника.<br/>            Только для чтения **float**. |
| [`bottom`](/slides/python-net/ru/aspose.slides/rectanglef/bottom/) | Получает координату y, равную сумме `y` и `height` этого прямоугольника.<br/>            Только для чтения **float**. |
| [`is_empty`](/slides/python-net/ru/aspose.slides/rectanglef/is_empty/) | Указывает, имеют ли все числовые свойства этого прямоугольника нулевые значения.<br/>            Только для чтения **bool**. |

## Методы

| Метод | Описание |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/ru/aspose.slides/rectanglef/contains/#float-float) | Определяет, содержится ли указанная точка в этом прямоугольнике. |
| [`contains(self, point)`](/slides/python-net/ru/aspose.slides/rectanglef/contains/#pointf) | Определяет, содержится ли указанная точка в этом прямоугольнике. |
| [`contains(self, rect)`](/slides/python-net/ru/aspose.slides/rectanglef/contains/#rectanglef) | Определяет, полностью ли прямоугольный регион, представленный `rect`, содержится в этом прямоугольнике. |

### Примечания

Прямоугольники сравниваются по их местоположению и размеру с помощью `==` и могут использоваться в качестве ключей словаря или элементов множества.

### См. также
* класс [`Rectangle`](/slides/python-net/ru/aspose.slides/rectangle)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)