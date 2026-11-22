---
title: ChartDataPoint class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint класс

Представляет точку данных серии.

Тип ChartDataPoint раскрывает следующие члены:

## Свойства

| Property | Description |
| :- | :- |
| [`x_value`](/slides/python-net/ru/aspose.slides.charts/chartdatapoint/x_value/) | XValue.<br/>            Только чтение [`IStringOrDoubleChartValue`](/slides/python-net/ru/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/ru/aspose.slides.charts/chartdatapoint/y_value/) | YValue.<br/>            Только чтение [`IDoubleChartValue`](/slides/python-net/ru/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/ru/aspose.slides.charts/chartdatapoint/bubble_size/) | BubbleSize.<br/>            Только чтение [`IDoubleChartValue`](/slides/python-net/ru/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/ru/aspose.slides.charts/chartdatapoint/value/) | Value.<br/>            Только чтение [`IDoubleChartValue`](/slides/python-net/ru/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/ru/aspose.slides.charts/chartdatapoint/size_value/) | Возвращает значение размера точки данных диаграммы.<br/>            Используется с диаграммами Treemap и Sunburst.<br/>            Только чтение [`IDoubleChartValue`](/slides/python-net/ru/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/ru/aspose.slides.charts/chartdatapoint/color_value/) | Возвращает значение цвета точки данных диаграммы.<br/>            Используется с диаграммами Map.<br/>            Только чтение [`IDoubleChartValue`](/slides/python-net/ru/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/ru/aspose.slides.charts/chartdatapoint/error_bars_custom_values/) | Представляет значения полос ошибок серии в случае пользовательского типа значения.<br/>            Только чтение [`IErrorBarsCustomValues`](/slides/python-net/ru/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/ru/aspose.slides.charts/chartdatapoint/label/) | Label.<br/>            Только чтение [`IDataLabel`](/slides/python-net/ru/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/ru/aspose.slides.charts/chartdatapoint/is_bubble_3d/) | Указывает, что у пузырей применяется 3-D эффект.<br/>            Чтение/запись **bool**. |
| [`explosion`](/slides/python-net/ru/aspose.slides.charts/chartdatapoint/explosion/) | Указывает величину, на которую точка данных должна быть смещена от центра круговой диаграммы.<br/>            Чтение/запись **int**. |
| [`format`](/slides/python-net/ru/aspose.slides.charts/chartdatapoint/format/) | Представляет свойства форматирования.<br/>            Чтение/запись [`IFormat`](/slides/python-net/ru/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/ru/aspose.slides.charts/chartdatapoint/marker/) | Указывает маркер данных.<br/>            Только чтение [`IMarker`](/slides/python-net/ru/aspose.slides.charts/imarker). |
| [`set_as_total`](/slides/python-net/ru/aspose.slides.charts/chartdatapoint/set_as_total/) | Устанавливает точку данных как итоговую. Применяется только для типа серии Waterfall. |
| [`related_legend_entry`](/slides/python-net/ru/aspose.slides.charts/chartdatapoint/related_legend_entry/) | Свойства соответствующей записи легенды в случае типа диаграммы из этого списка:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Только чтение [`ILegendEntryProperties`](/slides/python-net/ru/aspose.slides.charts/ilegendentryproperties). |
| [`data_point_levels`](/slides/python-net/ru/aspose.slides.charts/chartdatapoint/data_point_levels/) | Возвращает контейнер уровней точек данных. Применяется для серий Treeamp и Sunburst.<br/>            Индексация уровней точек данных начинается с нуля. |
| [`index`](/slides/python-net/ru/aspose.slides.charts/chartdatapoint/index/) |  |
| [`invert_if_negative`](/slides/python-net/ru/aspose.slides.charts/chartdatapoint/invert_if_negative/) | Указывает, что точка данных должна инвертировать свои цвета, если значение отрицательное.<br/>            Чтение/запись **bool**. |
| [`cached_value`](/slides/python-net/ru/aspose.slides.charts/chartdatapoint/cached_value/) | Получает кэшированное значение точки данных диаграммы.<br/>            Только чтение [`ICachedChartValue`](/slides/python-net/ru/aspose.slides.charts/icachedchartvalue). |
| [`cached_x_value`](/slides/python-net/ru/aspose.slides.charts/chartdatapoint/cached_x_value/) | Получает кэшированное значение X точки данных диаграммы.<br/>            Только чтение [`ICachedChartValue`](/slides/python-net/ru/aspose.slides.charts/icachedchartvalue). |
| [`cached_y_value`](/slides/python-net/ru/aspose.slides.charts/chartdatapoint/cached_y_value/) | Получает кэшированное значение Y точки данных диаграммы.<br/>            Только чтение [`ICachedChartValue`](/slides/python-net/ru/aspose.slides.charts/icachedchartvalue). |
| [`cached_bubble_size`](/slides/python-net/ru/aspose.slides.charts/chartdatapoint/cached_bubble_size/) | Получает кэшированное значение размера пузыря точки данных диаграммы.<br/>            Только чтение [`ICachedChartValue`](/slides/python-net/ru/aspose.slides.charts/icachedchartvalue). |
| [`actual_x`](/slides/python-net/ru/aspose.slides.charts/chartdatapoint/actual_x/) | Указывает фактическое положение по оси X (слева) элемента диаграммы относительно левого верхнего угла диаграммы.<br/>            Вызовите метод IChart.ValidateChartLayout() перед получением фактических значений.<br/>            Чтение **float**. |
| [`actual_y`](/slides/python-net/ru/aspose.slides.charts/chartdatapoint/actual_y/) | Указывает фактическую верхнюю позицию элемента диаграммы относительно левого верхнего угла диаграммы.<br/>            Вызовите метод IChart.ValidateChartLayout() перед получением фактических значений.<br/>            Чтение **float**. |
| [`actual_width`](/slides/python-net/ru/aspose.slides.charts/chartdatapoint/actual_width/) | Указывает фактическую ширину элемента диаграммы. Вызовите метод IChart.ValidateChartLayout() перед получением фактических значений.<br/>            Чтение **float**. |
| [`actual_height`](/slides/python-net/ru/aspose.slides.charts/chartdatapoint/actual_height/) | Указывает фактическую высоту элемента диаграммы. Вызовите метод IChart.ValidateChartLayout() перед получением фактических значений.<br/>            Чтение **float**. |

## Методы

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/ru/aspose.slides.charts/chartdatapoint/remove/#) | Удаляет DataPoint из серии диаграммы. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/ru/aspose.slides.charts/chartdatapoint/get_automatic_data_point_color/#) | Возвращает автоматический цвет точки данных на основе индекса серии, индекса точки данных, свойства ParentSeriesGroup.IsColorVaried и стиля диаграммы.<br/>            Этот цвет используется по умолчанию, если FillType равно NotDefined. |

### Смотрите также
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)