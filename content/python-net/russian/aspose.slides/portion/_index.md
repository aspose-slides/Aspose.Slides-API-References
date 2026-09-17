---
title: Portion class
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides/portion/
---
## Класс Portion

Представляет часть текста внутри текстового абзаца.

Тип Portion открывает следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ru/aspose.slides/portion/__init__/#) | Инициализирует новый экземпляр класса Portion. |
| [`__init__(self, str)`](/slides/python-net/ru/aspose.slides/portion/__init__/#str) | Инициализирует новый экземпляр класса Portion. |
| [`__init__(self, portion)`](/slides/python-net/ru/aspose.slides/portion/__init__/#portion) | Инициализирует новый экземпляр класса Portion. |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`portion_format`](/slides/python-net/ru/aspose.slides/portion/portion_format/) | Возвращает объект форматирования, который содержит явно заданные свойства форматирования текстовой части без применения наследования.<br/>            Только для чтения [`IPortionFormat`](/slides/python-net/ru/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/ru/aspose.slides/portion/text/) | Получает или задает простой текст части.<br/>            Чтение/запись **str**. |
| [`field`](/slides/python-net/ru/aspose.slides/portion/field/) | Возвращает поле этой части.<br/>            Только для чтения [`IField`](/slides/python-net/ru/aspose.slides/ifield). |
| [`slide`](/slides/python-net/ru/aspose.slides/portion/slide/) |  |
| [`presentation`](/slides/python-net/ru/aspose.slides/portion/presentation/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/ru/aspose.slides/portion/add_field/#ifieldtype) | Преобразует эту часть в автоматически обновляемое поле. |
| [`add_field(self, internal_string)`](/slides/python-net/ru/aspose.slides/portion/add_field/#str) | Преобразует эту часть в автоматически обновляемое поле. |
| [`remove_field(self)`](/slides/python-net/ru/aspose.slides/portion/remove_field/#) | Преобразует эту часть поля в простую часть. |
| [`get_rect(self)`](/slides/python-net/ru/aspose.slides/portion/get_rect/#) | Получить координаты прямоугольника, ограничивающего часть. Прямоугольник включает все строки<br/>            текста в части, включая пустые. |
| [`get_coordinates(self)`](/slides/python-net/ru/aspose.slides/portion/get_coordinates/#) | Получить координаты начала части. Координата X точки представляет начало части от первого символа, включая левый боковой вынос. Координата Y включает верхний боковой вынос. |

### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)