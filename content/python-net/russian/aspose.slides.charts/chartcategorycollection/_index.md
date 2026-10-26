---
title: ChartCategoryCollection class
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides.charts/chartcategorycollection/
---
## ChartCategoryCollection класс

Представляет коллекцию [`ChartCategory`](/slides/python-net/ru/aspose.slides.charts/chartcategory)

Тип ChartCategoryCollection предоставляет следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`use_cells`](/slides/python-net/ru/aspose.slides.charts/chartcategorycollection/use_cells/) | Если true, то лист используется для хранения категорий (в этом случае поддерживаются многоуровневые категории).<br/>            Если false, то лист НЕ используется для хранения значений (и этот случай не поддерживает <br/>            многоуровневые категории).<br/>            Чтение/запись **bool**. |
| [`grouping_level_count`](/slides/python-net/ru/aspose.slides.charts/chartcategorycollection/grouping_level_count/) | Возвращает количество уровней группировки категорий, используемых.<br/>            Больше одного для многоуровневых категорий.<br/>            Только для чтения **int**. |

Получает элемент по указанному индексу.

## Индексатор

| Имя | Описание |
| :- | :- |
| [`[index]`](/slides/python-net/ru/aspose.slides.charts/chartcategorycollection/__getitem__/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/ru/aspose.slides.charts/chartcategorycollection/add/#ichartdatacell) | Если категория существует в коллекции, вернуть её. Иначе создаёт новую категорию диаграммы из <br/>            [`IChartDataCell`](/slides/python-net/ru/aspose.slides.charts/ichartdatacell) и добавляет её в коллекцию. |
| [`add(self, value)`](/slides/python-net/ru/aspose.slides.charts/chartcategorycollection/add/#any) | Создаёт новый [`ChartCategory`](/slides/python-net/ru/aspose.slides.charts/chartcategory) из значения и добавляет его в коллекцию. |
| [`index_of(self, value)`](/slides/python-net/ru/aspose.slides.charts/chartcategorycollection/index_of/#ichartcategory) | Ищет указанный [`ChartCategory`](/slides/python-net/ru/aspose.slides.charts/chartcategory) и возвращает нулевой индекс первого вхождения в всю коллекцию. |
| [`remove(self, value)`](/slides/python-net/ru/aspose.slides.charts/chartcategorycollection/remove/#ichartcategory) | Удаляет указанное значение. |
| [`remove_at(self, index)`](/slides/python-net/ru/aspose.slides.charts/chartcategorycollection/remove_at/#int) | Удаляет элемент по указанному индексу. |
| [`clear(self)`](/slides/python-net/ru/aspose.slides.charts/chartcategorycollection/clear/#) | Удаляет все элементы из коллекции. |

### См. также
* класс [`ChartCategory`](/slides/python-net/ru/aspose.slides.charts/chartcategory)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)