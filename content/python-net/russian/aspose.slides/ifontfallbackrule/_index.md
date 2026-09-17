---
title: IFontFallBackRule class
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides/ifontfallbackrule/
---
## IFontFallBackRule класс

Представляет правило подстановки шрифтов

Тип IFontFallBackRule раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`range_start_index`](/slides/python-net/ru/aspose.slides/ifontfallbackrule/range_start_index/) | Получить первый индекс непрерывного диапазона Unicode. |
| [`range_end_index`](/slides/python-net/ru/aspose.slides/ifontfallbackrule/range_end_index/) | Получить последний индекс непрерывного диапазона Unicode. |
| [`count`](/slides/python-net/ru/aspose.slides/ifontfallbackrule/count/) | Возвращает количество шрифтов, действительно определённых для диапазона. |

Получает имя шрифта по указанному индексу.

## Индексатор

| Имя | Описание |
| :- | :- |
| [`[index]`](/slides/python-net/ru/aspose.slides/ifontfallbackrule/__getitem__/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`add_fall_back_fonts(self, font_name)`](/slides/python-net/ru/aspose.slides/ifontfallbackrule/add_fall_back_fonts/#str) | Добавляет новый шрифт(ы) в список шрифтов FallBack. |
| [`add_fall_back_fonts(self, font_names)`](/slides/python-net/ru/aspose.slides/ifontfallbackrule/add_fall_back_fonts/#liststr) | Добавляет новый шрифт в список шрифтов FallBack. |
| [`to_array(self)`](/slides/python-net/ru/aspose.slides/ifontfallbackrule/to_array/#) | Создаёт и возвращает массив со всеми шрифтами FallBack для этого правила. |
| [`to_array(self, start_index, count)`](/slides/python-net/ru/aspose.slides/ifontfallbackrule/to_array/#int-int) | Создаёт и возвращает массив со всеми шрифтами FallBack из указанного диапазона в списке. |
| [`clear(self)`](/slides/python-net/ru/aspose.slides/ifontfallbackrule/clear/#) | Удаляет все шрифты из списка. |
| [`remove(self, font_name)`](/slides/python-net/ru/aspose.slides/ifontfallbackrule/remove/#str) | Удаляет первое вхождение определённого шрифта FallBack из списка. |
| [`remove_at(self, index)`](/slides/python-net/ru/aspose.slides/ifontfallbackrule/remove_at/#int) | Удаляет шрифт FallBack по указанному индексу в списке. |
| [`index_of(self, font_name)`](/slides/python-net/ru/aspose.slides/ifontfallbackrule/index_of/#str) | Возвращает индекс указанного правила в коллекции. |

### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)