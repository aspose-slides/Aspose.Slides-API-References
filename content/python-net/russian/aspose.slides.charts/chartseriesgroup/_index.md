---
title: ChartSeriesGroup class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup класс

Представляет группу рядов.

Тип ChartSeriesGroup содержит следующие члены:

## Свойства

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/ru/aspose.slides.charts/chartseriesgroup/type/) | Возвращает тип этой группы рядов.<br/>            Только для чтения [`CombinableSeriesTypesGroup`](/slides/python-net/ru/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/ru/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | Указывает, отображаются ли ряды этой группы на вторичной оси.<br/>            Только для чтения **bool**. |
| [`series`](/slides/python-net/ru/aspose.slides.charts/chartseriesgroup/series/) | Возвращает коллекцию рядов.<br/>            Только для чтения [`IChartSeriesReadonlyCollection`](/slides/python-net/ru/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/ru/aspose.slides.charts/chartseriesgroup/up_down_bars/) | Обеспечивает доступ к линиям верх/низ графика Line или Stock.<br/>            Только для чтения [`IUpDownBarsManager`](/slides/python-net/ru/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/ru/aspose.slides.charts/chartseriesgroup/gap_width/) | Получает или задает расстояние между кластерами столбцов или колонок, в процентах от ширины столбца.<br/>            Значение должно быть от 0 до 500.<br/>            Чтение/запись **int**. |
| [`gap_depth`](/slides/python-net/ru/aspose.slides.charts/chartseriesgroup/gap_depth/) | Получает или задает расстояние между данными рядами в 3D-графике, в процентах от ширины маркера.<br/>            Значение должно быть от 0 до 500.<br/>            Чтение/запись **int**. |
| [`first_slice_angle`](/slides/python-net/ru/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | Получает или задает угол первого сектора круга или кольца,<br/>            в градусах (по часовой стрелке от верхней позиции, от 0 до 360 градусов).<br/>            Чтение/запись **int**. |
| [`doughnut_hole_size`](/slides/python-net/ru/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | Указывает размер отверстия в кольцевом графике (может быть от 0 до 90 процентов от размера области построения).<br/>            Чтение/запись **int**. |
| [`overlap`](/slides/python-net/ru/aspose.slides.charts/chartseriesgroup/overlap/) | Указывает, насколько столбцы и колонки должны перекрываться на 2-D графиках, в процентах (от -100% до 100%).<br/>             - -100%: Максимальное расстояние (столбцы полностью разъединены).<br/>             - 0%: Столбцы расположены рядом без перекрытия и промежутка.<br/>             - 100%: Максимальное перекрытие (столбцы полностью накладываются друг на друга).<br/>             Это свойство поддерживает чтение/запись **int**. |
| [`second_pie_size`](/slides/python-net/ru/aspose.slides.charts/chartseriesgroup/second_pie_size/) | Указывает размер второго сектора или столбца в диаграмме «pie-of-pie» или «bar-of-pie», в процентах от размера первого сектора (может быть от 5 до 200 процентов).<br/>            Чтение/запись **int**. |
| [`bubble_size_representation`](/slides/python-net/ru/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | Указывает, как значения размеров пузырей отображаются на пузырчатой диаграмме.<br/>            Чтение/запись [`BubbleSizeRepresentationType`](/slides/python-net/ru/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/ru/aspose.slides.charts/chartseriesgroup/pie_split_position/) | Указывает значение, которое будет использоваться для определения, какие точки данных находятся во втором секторе или столбце в диаграмме «pie-of-pie» или «bar-of-pie».<br/>            Используется вместе со свойством PieSplitBy.<br/>            Чтение/запись **float**. |
| [`pie_split_by`](/slides/python-net/ru/aspose.slides.charts/chartseriesgroup/pie_split_by/) | Указывает, как определить, какие точки данных находятся во втором секторе или столбце в диаграмме «pie-of-pie» или «bar-of-pie».<br/>            Чтение/запись [`PieSplitType`](/slides/python-net/ru/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/ru/aspose.slides.charts/chartseriesgroup/is_color_varied/) | Указывает, что каждый маркер данных в ряду имеет разный цвет.<br/>            Чтение/запись **bool**. |
| [`has_series_lines`](/slides/python-net/ru/aspose.slides.charts/chartseriesgroup/has_series_lines/) | True если у диаграммы есть линии рядов. Применяется к вложенным столбчатым и OfPie диаграммам.<br/>            Чтение/запись **bool**. |
| [`hi_low_lines_format`](/slides/python-net/ru/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | Указывает формат HiLowLines.<br/>            HiLowLines применяется к типам диаграмм HiLowClose, OpenHiLowClose, VolumeHiLowClose и VolumeOpenHiLowClose. |
| [`bubble_size_scale`](/slides/python-net/ru/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | Указывает коэффициент масштабирования для пузырчатой диаграммы (может быть от 0 до 300 процентов от размера по умолчанию).<br/>            Чтение/запись **int**. |
| [`pie_split_custom_points`](/slides/python-net/ru/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | Пользовательская информация о разбиении для диаграммы «pie-of-pie» или «bar-of-pie» с пользовательским разбиением.<br/>            Содержит точки данных, которые будут нарисованы во втором секторе или столбце в диаграмме «pie-of-pie» или <br/>            «bar-of-pie».<br/>            Только для чтения [`PieSplitCustomPointCollection`](/slides/python-net/ru/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/ru/aspose.slides.charts/chartseriesgroup/chart/) | Возвращает родительскую диаграмму.<br/>            Только для чтения [`IChart`](/slides/python-net/ru/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/ru/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/ru/aspose.slides.charts/chartseriesgroup/presentation/) |  |

Получает элемент по указанному индексу.

## Индексатор

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/ru/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |

### Замечания

1) См. резюме и замечания для класса ChartSeriesGroupCollection и перечисления CombinableSeriesTypesGroup.  
2) Группа рядов содержит некоторые свойства рядов, общие для каждого ряда в группе («series group properties»).  
«Series group properties» в классе ChartSeriesGroup — чтение/запись.  
Каждое из «series group properties» может иметь только-для-чтения проекцию в классе ChartSeries.

### См. также
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)