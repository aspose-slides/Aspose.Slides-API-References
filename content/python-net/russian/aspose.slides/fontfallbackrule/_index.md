---
title: FontFallBackRule class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/fontfallbackrule/
---
## FontFallBackRule класс

Представляет правило подстановки шрифтов

Тип FontFallBackRule раскрывает следующие члены:

## Конструкторы

| Constructor | Description |
| :- | :- |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/ru/aspose.slides/fontfallbackrule/__init__/#int-int-str) | Создает новый экземпляр. |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/ru/aspose.slides/fontfallbackrule/__init__/#int-int-liststr) | Создает новый экземпляр. |

## Свойства

| Property | Description |
| :- | :- |
| [`range_start_index`](/slides/python-net/ru/aspose.slides/fontfallbackrule/range_start_index/) | Получить первый индекс непрерывного диапазона Unicode. |
| [`range_end_index`](/slides/python-net/ru/aspose.slides/fontfallbackrule/range_end_index/) | Получить последний индекс непрерывного диапазона Unicode. |
| [`count`](/slides/python-net/ru/aspose.slides/fontfallbackrule/count/) | Получает количество шрифтов, фактически определенных для диапазона.<br/>            Только для чтения **int**. |

Получает имя шрифта по указанному индексу.  
Только для чтения [`IFontFallBackRule`](/slides/python-net/ru/aspose.slides/ifontfallbackrule).

## Индексатор

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/ru/aspose.slides/fontfallbackrule/__getitem__/) |  |

## Методы

| Method | Description |
| :- | :- |
| [`add_fall_back_fonts(self, font_name)`](/slides/python-net/ru/aspose.slides/fontfallbackrule/add_fall_back_fonts/#str) | Добавляет новый шрифт(ы) в список шрифтов FallBack. |
| [`add_fall_back_fonts(self, font_names)`](/slides/python-net/ru/aspose.slides/fontfallbackrule/add_fall_back_fonts/#liststr) | Добавляет новые шрифты в список шрифтов FallBack. |
| [`to_array(self)`](/slides/python-net/ru/aspose.slides/fontfallbackrule/to_array/#) | Создаёт и возвращает массив со всеми шрифтами FallBack для этого правила. |
| [`to_array(self, start_index, count)`](/slides/python-net/ru/aspose.slides/fontfallbackrule/to_array/#int-int) | Создаёт и возвращает массив со всеми шрифтами FallBack из указанного диапазона в списке. |
| [`clear(self)`](/slides/python-net/ru/aspose.slides/fontfallbackrule/clear/#) | Удаляет все шрифты из списка. |
| [`remove(self, font_name)`](/slides/python-net/ru/aspose.slides/fontfallbackrule/remove/#str) | Удаляет первое вхождение конкретного шрифта FallBack из списка. |
| [`remove_at(self, index)`](/slides/python-net/ru/aspose.slides/fontfallbackrule/remove_at/#int) | Удаляет шрифт FallBack по указанному индексу в списке. |
| [`index_of(self, font_name)`](/slides/python-net/ru/aspose.slides/fontfallbackrule/index_of/#str) | Возвращает индекс указанного правила в коллекции. |

### См. также
* класс [`IFontFallBackRule`](/slides/python-net/ru/aspose.slides/ifontfallbackrule)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)