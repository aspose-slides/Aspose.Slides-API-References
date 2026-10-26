---
title: IChartSeriesGroup class
second_title: Aspose.Slides для Python через .NET – справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup класс

Представляет группу серий.

Тип IChartSeriesGroup раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`type`](/slides/python-net/ru/aspose.slides.charts/ichartseriesgroup/type/) | Возвращает тип этой группы серий.<br/>            Только для чтения [`CombinableSeriesTypesGroup`](/slides/python-net/ru/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/ru/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | Указывает, построены ли серии этой группы на вторичной оси.<br/>            Только для чтения **bool**. |
| [`series`](/slides/python-net/ru/aspose.slides.charts/ichartseriesgroup/series/) | Возвращает только для чтения коллекцию серий диаграммы.<br/>            Только для чтения [`IChartSeriesReadonlyCollection`](/slides/python-net/ru/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/ru/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | Обеспечивает доступ к полосам вверх/вниз в линейной или биржевой диаграмме.<br/>            Только для чтения [`IUpDownBarsManager`](/slides/python-net/ru/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/ru/aspose.slides.charts/ichartseriesgroup/gap_width/) | Указывает пространство между кластерами столбцов или колонок в процентах от ширины столбца или колонки.<br/>            Чтение/запись **int**. |
| [`gap_depth`](/slides/python-net/ru/aspose.slides.charts/ichartseriesgroup/gap_depth/) | Возвращает или задает расстояние в процентах от ширины маркера между сериями данных в 3D-диаграмме.<br/>            Чтение/запись **int**. |
| [`first_slice_angle`](/slides/python-net/ru/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | Получает или задает угол первого сектора круговой или кольцевой диаграммы,<br/>            в градусах (по часовой стрелке от верха, от 0 до 360 градусов).<br/>            Чтение/запись **int**. |
| [`is_color_varied`](/slides/python-net/ru/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | Указывает, что каждый маркер данных в серии имеет разный цвет.<br/>            Чтение/запись **bool**. |
| [`has_series_lines`](/slides/python-net/ru/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | Истина, если у диаграммы есть линии серии. Применяется к сложенным столбчатым и диаграммам OfPie.<br/>            Чтение/запись **bool**. |
| [`overlap`](/slides/python-net/ru/aspose.slides.charts/ichartseriesgroup/overlap/) | Указывает, насколько столбцы и колонки должны перекрываться на 2-D диаграммах, в процентах (от -100% до 100%).<br/>             - -100%: Максимальное расстояние (столбцы полностью разделены).<br/>             - 0%: Столбцы размещаются рядом без перекрытия и без промежутка.<br/>             - 100%: Максимальное перекрытие (столбцы полностью перекрывают друг друга).<br/>             Это свойство — чтение/запись **int**. |
| [`second_pie_size`](/slides/python-net/ru/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | Указывает размер второго сектора или столбца в диаграмме pie-of-pie или bar-of-pie в процентах от размера первого сектора (может быть от 5 до 200 процентов).<br/>            Чтение/запись **int**. |
| [`pie_split_position`](/slides/python-net/ru/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | Указывает значение, которое будет использоваться для определения, какие точки данных находятся во втором секторе или столбце в диаграмме pie-of-pie или bar-of-pie.<br/>            Используется совместно со свойством PieSplitBy.<br/>            Чтение/запись **float**. |
| [`pie_split_by`](/slides/python-net/ru/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | Указывает, как определить, какие точки данных находятся во втором секторе или столбце в диаграмме pie-of-pie или bar-of-pie.<br/>            Чтение/запись [`PieSplitType`](/slides/python-net/ru/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/ru/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | Информация о пользовательском разделении для диаграммы pie-of-pie или bar-of-pie с пользовательским разделением.<br/>            Содержит точки данных, которые должны быть отрисованы во втором секторе или столбце диаграммы pie-of-pie или bar-of-pie.<br/>            Только для чтения [`IPieSplitCustomPointCollection`](/slides/python-net/ru/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`doughnut_hole_size`](/slides/python-net/ru/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | Указывает размер отверстия в кольцевой диаграмме (может быть от 10 до 90 процентов от размера области построения).<br/>            Чтение/запись **int**. |
| [`bubble_size_scale`](/slides/python-net/ru/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | Указывает коэффициент масштаба для пузырьковой диаграммы (может быть от 0 до 300 процентов от стандартного размера).<br/>            Чтение/запись **int**. |
| [`hi_low_lines_format`](/slides/python-net/ru/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | Указывает формат HiLowLines.<br/>            HiLowLines применяется к типам диаграмм HiLowClose, OpenHiLowClose, VolumeHiLowClose и VolumeOpenHiLowClose. |
| [`bubble_size_representation`](/slides/python-net/ru/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | Указывает, как значения размеров пузырей представлены в пузырьковой диаграмме.<br/>            Чтение/запись [`BubbleSizeRepresentationType`](/slides/python-net/ru/aspose.slides.charts/bubblesizerepresentationtype). |
| [`chart`](/slides/python-net/ru/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/ru/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/ru/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

Получает элемент по указанному индексу.

## Индексатор

| Имя | Описание |
| :- | :- |
| [`[index]`](/slides/python-net/ru/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |

### Примечания

1) Смотрите резюме и примечания к классу ChartSeriesGroupCollection и перечислению CombinableSeriesTypesGroup enum.
2) Группа серий содержит некоторые свойства серий, общие для каждой серии в группе («свойства группы серий»).
"Series group properties" в классе ChartSeriesGroup — чтение/запись.
Каждое из «свойств группы серий» может иметь только для чтения проекцию в классе ChartSeries.

### См. также
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)