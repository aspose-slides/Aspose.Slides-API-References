---
title: IDataLabelCollection class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection класс

Представляет метки серии.

Тип IDataLabelCollection предоставляет следующие члены:

## Свойства

| Сproperty | Описание |
| :- | :- |
| [`default_data_label_format`](/slides/python-net/ru/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | Возвращает формат по умолчанию для всех меток данных в коллекции.<br/>            Только для чтения [`IDataLabelFormat`](/slides/python-net/ru/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/ru/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | Представляет формат линий-выводов меток данных.<br/>            Только для чтения [`IChartLinesFormat`](/slides/python-net/ru/aspose.slides.charts/ichartlinesformat). |
| [`is_visible`](/slides/python-net/ru/aspose.slides.charts/idatalabelcollection/is_visible/) | False означает, что метка данных по умолчанию не видима (и поэтому все <br/>            Show*-flags (ShowValue, ...) свойства DefaultDataLabelFormat имеют значение false).<br/>            Только для чтения **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/ru/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | Получает количество видимых меток данных в коллекции.<br/>            Только для чтения **int**. |
| [`count`](/slides/python-net/ru/aspose.slides.charts/idatalabelcollection/count/) | Получает количество всех меток данных в коллекции.<br/>            Только для чтения **int**. |
| [`parent_series`](/slides/python-net/ru/aspose.slides.charts/idatalabelcollection/parent_series/) | Возвращает родительскую серию диаграммы.<br/>            Только для чтения [`IChartSeries`](/slides/python-net/ru/aspose.slides.charts/ichartseries). |
| [`chart`](/slides/python-net/ru/aspose.slides.charts/idatalabelcollection/chart/) |  |
| [`slide`](/slides/python-net/ru/aspose.slides.charts/idatalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/ru/aspose.slides.charts/idatalabelcollection/presentation/) |  |

Получает метку данных для точки данных с указанным индексом.

## Индексатор

| Имя | Описание |
| :- | :- |
| [`[index]`](/slides/python-net/ru/aspose.slides.charts/idatalabelcollection/__getitem__/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`hide(self)`](/slides/python-net/ru/aspose.slides.charts/idatalabelcollection/hide/#) | Сделать метку данных скрытой по умолчанию, установив все Show*-flags (ShowValue, ...) свойства DefaultDataLabelFormat в состояние false.<br/>            После этого IsVisible будет false. |
| [`index_of(self, value)`](/slides/python-net/ru/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | Возвращает индекс указанной DataLabel в коллекции. |

### См. также
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)