---
title: ISectionCollection class
second_title: Aspose.Slides для Python через .NET API Справочник
description: 
type: docs
url: /ru/aspose.slides/isectioncollection/
---
## ISectionCollection класс

Представляет коллекцию секций.

Тип ISectionCollection раскрывает следующие члены:

Получает элемент по указанному индексу.  
Только для чтения [`ISection`](/slides/python-net/ru/aspose.slides/isection).

## Индексатор

| Имя | Описание |
| :- | :- |
| [`[index]`](/slides/python-net/ru/aspose.slides/isectioncollection/__getitem__/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`add_section(self, name, started_from_slide)`](/slides/python-net/ru/aspose.slides/isectioncollection/add_section/#str-islide) | Добавляет новую секцию, начинающуюся с конкретного слайда. |
| [`add_empty_section(self, name, index)`](/slides/python-net/ru/aspose.slides/isectioncollection/add_empty_section/#str-int) | Добавляет пустую секцию в указанную позицию коллекции. |
| [`remove_section_with_slides(self, section)`](/slides/python-net/ru/aspose.slides/isectioncollection/remove_section_with_slides/#isection) | Удаляет секцию и слайды, содержащиеся в ней. |
| [`remove_section(self, section)`](/slides/python-net/ru/aspose.slides/isectioncollection/remove_section/#isection) | Удаляет секцию. Слайды, содержащиеся в секции, будут объединены с предыдущей секцией. |
| [`reorder_section_with_slides(self, section, index)`](/slides/python-net/ru/aspose.slides/isectioncollection/reorder_section_with_slides/#isection-int) | Перемещает секцию и её слайды из коллекции в указанную позицию. |
| [`append_empty_section(self, name)`](/slides/python-net/ru/aspose.slides/isectioncollection/append_empty_section/#str) | Добавляет пустую секцию в конец коллекции. |
| [`index_of(self, section)`](/slides/python-net/ru/aspose.slides/isectioncollection/index_of/#isection) | Возвращает индекс указанной секции в коллекции. |
| [`clear(self)`](/slides/python-net/ru/aspose.slides/isectioncollection/clear/#) | Удаляет все секции из коллекции. |

### См. также
* класс [`ISection`](/slides/python-net/ru/aspose.slides/isection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)