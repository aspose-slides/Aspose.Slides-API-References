---
title: Point class
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides.animation/point/
---
## Point класс

Представляет точку анимации.

Тип Point раскрывает следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ru/aspose.slides.animation/point/__init__/#) | Конструктор по умолчанию. |
| [`__init__(self, time, value, formula)`](/slides/python-net/ru/aspose.slides.animation/point/__init__/#float-any-str) | Создать точку анимации с временем, значением и формулой. |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`time`](/slides/python-net/ru/aspose.slides.animation/point/time/) | Представляет значение времени.<br/>            Чтение/запись **float**. |
| [`value`](/slides/python-net/ru/aspose.slides.animation/point/value/) | Представляет значение точки.<br/>            Только: bool, ColorFormat, float, int, string.<br/>            Чтение/запись **any**. |
| [`formula`](/slides/python-net/ru/aspose.slides.animation/point/formula/) | Формулы внутри значений атрибутов from, to, by могут состоять из следующих элементов:<br/>            Стандартные арифметические операторы: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)<br/>            Константы: ‘pi’ ‘e’<br/>            Условные операторы: ‘abs’, ‘min’, ‘max’, ‘?’ (if)<br/>            Операторы сравнения: '==', '>=', '', '!=', '!'<br/>            Тригонометрические операторы: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’<br/>            Натуральный логарифм ‘ln()’<br/>            Ссылки на свойства (host supported properties)<br/>            <br/>            например: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"<br/>            Чтение/запись **str**. |

### См. также
* модуль [`aspose.slides.animation`](/slides/python-net/ru/aspose.slides.animation)
* библиотека [`Aspose.Slides`](/slides/python-net)