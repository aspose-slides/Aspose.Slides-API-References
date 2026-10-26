---
title: MathPortion class
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides.mathtext/mathportion/
---
## MathPortion класс

Represents a portion with mathematical context inside.

**Inheritance:**[`MathPortion`](/slides/python-net/ru/aspose.slides.mathtext/mathportion) → [`Portion`](/slides/python-net/ru/aspose.slides/portion)

The MathPortion type exposes the following members:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathportion/__init__/#) | Инициализирует новый экземпляр класса MathPortion. |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`portion_format`](/slides/python-net/ru/aspose.slides.mathtext/mathportion/portion_format/) | Возвращает объект форматирования, содержащий явно заданные свойства форматирования текстовой части без применения наследования.<br/>            Только для чтения [`IPortionFormat`](/slides/python-net/ru/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/ru/aspose.slides.mathtext/mathportion/text/) | Получает или задает простой текст части.<br/>            Чтение/запись **str**. |
| [`field`](/slides/python-net/ru/aspose.slides.mathtext/mathportion/field/) | Возвращает поле этой части.<br/>            Только для чтения [`IField`](/slides/python-net/ru/aspose.slides/ifield). |
| [`math_paragraph`](/slides/python-net/ru/aspose.slides.mathtext/mathportion/math_paragraph/) | Математический абзац |
| [`slide`](/slides/python-net/ru/aspose.slides.mathtext/mathportion/slide/) |  |
| [`presentation`](/slides/python-net/ru/aspose.slides.mathtext/mathportion/presentation/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathportion/add_field/#ifieldtype) | Преобразует эту часть в автоматически обновляемое поле. |
| [`add_field(self, internal_string)`](/slides/python-net/ru/aspose.slides.mathtext/mathportion/add_field/#str) | Преобразует эту часть в автоматически обновляемое поле. |
| [`remove_field(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathportion/remove_field/#) | Преобразует эту часть поля в простую часть. |
| [`get_rect(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathportion/get_rect/#) | Получить координаты прямоугольника, ограничивающего часть. Прямоугольник включает все строки текста в части, включая пустые. |
| [`get_coordinates(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathportion/get_coordinates/#) | Получить координаты начала части. Координата X точки представляет начало части с первого символа, включая левый отступ. Координата Y включает верхний отступ. |

### См. также
* класс [`MathPortion`](/slides/python-net/ru/aspose.slides.mathtext/mathportion)
* класс [`Portion`](/slides/python-net/ru/aspose.slides/portion)
* модуль [`aspose.slides.mathtext`](/slides/python-net/ru/aspose.slides.mathtext)
* библиотека [`Aspose.Slides`](/slides/python-net)