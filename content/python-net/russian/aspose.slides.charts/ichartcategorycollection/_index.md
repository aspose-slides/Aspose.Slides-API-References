---
title: IChartCategoryCollection class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/ichartcategorycollection/
---
## IChartCategoryCollection класс

Представляет коллекцию [`IChartCategory`](/slides/python-net/ru/aspose.slides.charts/ichartcategory)

Тип IChartCategoryCollection раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`use_cells`](/slides/python-net/ru/aspose.slides.charts/ichartcategorycollection/use_cells/) | Если true, то лист используется для хранения категорий (в этом случае поддерживаются многоуровневые категории).<br/>            Если false, то лист НЕ используется для хранения значений (и в этом случае не поддерживаются <br/>            многоуровневые категории).<br/>            Чтение/запись **bool**. |
| [`grouping_level_count`](/slides/python-net/ru/aspose.slides.charts/ichartcategorycollection/grouping_level_count/) | Возвращает количество уровней группировки категорий, используемых.<br/>            Больше одного для многоуровневых категорий.<br/>            Только чтение **int**. |

Получает элемент по указанному индексу.

## Индексатор

| Имя | Описание |
| :- | :- |
| [`[index]`](/slides/python-net/ru/aspose.slides.charts/ichartcategorycollection/__getitem__/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/ru/aspose.slides.charts/ichartcategorycollection/add/#ichartdatacell) | Если категория существует в коллекции, вернуть её. Иначе создаёт новую категорию диаграммы из <br/>            [`IChartDataCell`](/slides/python-net/ru/aspose.slides.charts/ichartdatacell) и добавляет её в коллекцию. |
| [`add(self, value)`](/slides/python-net/ru/aspose.slides.charts/ichartcategorycollection/add/#any) | Создаёт новый [`IChartCategory`](/slides/python-net/ru/aspose.slides.charts/ichartcategory) из значения и добавляет его в коллекцию. |
| [`index_of(self, value)`](/slides/python-net/ru/aspose.slides.charts/ichartcategorycollection/index_of/#ichartcategory) | Ищет указанный [`IChartCategory`](/slides/python-net/ru/aspose.slides.charts/ichartcategory) и возвращает нулевой индекс первого вхождения во всей коллекции |
| [`remove(self, value)`](/slides/python-net/ru/aspose.slides.charts/ichartcategorycollection/remove/#ichartcategory) | Удаляет указанное значение. |
| [`remove_at(self, index)`](/slides/python-net/ru/aspose.slides.charts/ichartcategorycollection/remove_at/#int) | Удаляет элемент по заданному индексу. |
| [`clear(self)`](/slides/python-net/ru/aspose.slides.charts/ichartcategorycollection/clear/#) | Удаляет все элементы из коллекции. |

### См. также
* класс [`IChartCategory`](/slides/python-net/ru/aspose.slides.charts/ichartcategory)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)