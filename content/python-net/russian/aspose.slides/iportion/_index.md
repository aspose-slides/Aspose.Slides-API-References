---
title: IPortion class
second_title: Aspose.Slides для Python через .NET API справка
description: 
type: docs
url: /ru/aspose.slides/iportion/
---
## IPortion класс

Представляет собой часть текста внутри текстового абзаца.

Тип IPortion предоставляет следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`portion_format`](/slides/python-net/ru/aspose.slides/iportion/portion_format/) | Возвращает объект форматирования, который содержит явно установленные свойства форматирования части текста без применения наследования.<br/>            Только для чтения [`IPortionFormat`](/slides/python-net/ru/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/ru/aspose.slides/iportion/text/) | Получает или задает простой текст части.<br/>            Чтение/запись **str**. |
| [`field`](/slides/python-net/ru/aspose.slides/iportion/field/) | Возвращает поле этой части.<br/>            Только для чтения [`IField`](/slides/python-net/ru/aspose.slides/ifield). |
| [`slide`](/slides/python-net/ru/aspose.slides/iportion/slide/) |  |
| [`presentation`](/slides/python-net/ru/aspose.slides/iportion/presentation/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/ru/aspose.slides/iportion/add_field/#ifieldtype) | Преобразует эту часть в автоматически обновляемое поле. |
| [`add_field(self, internal_string)`](/slides/python-net/ru/aspose.slides/iportion/add_field/#str) | Преобразует эту часть в автоматически обновляемое поле. |
| [`remove_field(self)`](/slides/python-net/ru/aspose.slides/iportion/remove_field/#) | Преобразует эту часть поля в простую часть. |
| [`get_rect(self)`](/slides/python-net/ru/aspose.slides/iportion/get_rect/#) | Получает координаты прямоугольника, ограничивающего часть. Прямоугольник включает все строки<br/>             текста в части, включая пустые. |
| [`get_coordinates(self)`](/slides/python-net/ru/aspose.slides/iportion/get_coordinates/#) | Получает координаты начала части. Координата X точки представляет начало части с первого символа, включая левый боковой отступ. Координата Y включает верхний боковой отступ. |


### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)