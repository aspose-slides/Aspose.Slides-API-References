---
title: DataLabelCollection class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/datalabelcollection/
---
## DataLabelCollection класс

Представляет метки серии.

Тип DataLabelCollection раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`chart`](/slides/python-net/ru/aspose.slides.charts/datalabelcollection/chart/) | Возвращает родительскую диаграмму.<br/>            Только для чтения [`IChart`](/slides/python-net/ru/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/ru/aspose.slides.charts/datalabelcollection/is_visible/) | False означает, что метка данных не видна по умолчанию (и поэтому все <br/>            Show*-flags (ShowValue, ...) свойства DefaultDataLabelFormat имеют значение false).<br/>            Только для чтения **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/ru/aspose.slides.charts/datalabelcollection/count_of_visible_data_labels/) | Возвращает количество видимых меток данных в коллекции.<br/>            Только для чтения **int**. |
| [`count`](/slides/python-net/ru/aspose.slides.charts/datalabelcollection/count/) | Возвращает количество всех меток данных в коллекции.<br/>            Только для чтения **int**. |
| [`default_data_label_format`](/slides/python-net/ru/aspose.slides.charts/datalabelcollection/default_data_label_format/) | Возвращает формат метки данных по умолчанию.<br/>            Только для чтения [`IDataLabelFormat`](/slides/python-net/ru/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/ru/aspose.slides.charts/datalabelcollection/leader_lines_format/) | Представляет формат линий-выделителей меток данных.<br/>             Только для чтения [`IChartLinesFormat`](/slides/python-net/ru/aspose.slides.charts/ichartlinesformat). |
| [`parent_series`](/slides/python-net/ru/aspose.slides.charts/datalabelcollection/parent_series/) | Возвращает родительскую серию.<br/>            Только для чтения [`IChartSeries`](/slides/python-net/ru/aspose.slides.charts/ichartseries). |
| [`slide`](/slides/python-net/ru/aspose.slides.charts/datalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/ru/aspose.slides.charts/datalabelcollection/presentation/) |  |

Возвращает метку данных для точки данных с указанным индексом.

## Индексатор

| Имя | Описание |
| :- | :- |
| [`[index]`](/slides/python-net/ru/aspose.slides.charts/datalabelcollection/__getitem__/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`hide(self)`](/slides/python-net/ru/aspose.slides.charts/datalabelcollection/hide/#) | Сделать метку данных скрытой по умолчанию, установив все Show*-flags (ShowValue, ...) свойства DefaultDataLabelFormat в состояние false.<br/>            IsVisible будет false после этого. |
| [`index_of(self, value)`](/slides/python-net/ru/aspose.slides.charts/datalabelcollection/index_of/#idatalabel) | Возвращает индекс указанной DataLabel в коллекции. |


### См. также
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)