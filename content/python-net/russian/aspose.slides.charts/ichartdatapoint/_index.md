---
title: IChartDataPoint class
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint класс

Представляет точку данных серии.

Тип IChartDataPoint раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`x_value`](/slides/python-net/ru/aspose.slides.charts/ichartdatapoint/x_value/) | Возвращает значение x точки данных диаграммы.<br/>            Только для чтения [`IStringOrDoubleChartValue`](/slides/python-net/ru/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/ru/aspose.slides.charts/ichartdatapoint/y_value/) | Возвращает значение y точки данных диаграммы.<br/>            Только для чтения [`IDoubleChartValue`](/slides/python-net/ru/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/ru/aspose.slides.charts/ichartdatapoint/bubble_size/) | Возвращает размер пузыря точки данных диаграммы.<br/>            Только для чтения [`IDoubleChartValue`](/slides/python-net/ru/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/ru/aspose.slides.charts/ichartdatapoint/value/) | Возвращает значение точки данных диаграммы.<br/>            Только для чтения [`IDoubleChartValue`](/slides/python-net/ru/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/ru/aspose.slides.charts/ichartdatapoint/size_value/) | Возвращает размерное значение точки данных диаграммы.<br/>            Используется с диаграммами Treemap и Sunburst. <br/>            Только для чтения [`IDoubleChartValue`](/slides/python-net/ru/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/ru/aspose.slides.charts/ichartdatapoint/color_value/) | Возвращает значение цвета точки данных диаграммы.<br/>            Используется с картографическими диаграммами. <br/>            Только для чтения [`IDoubleChartValue`](/slides/python-net/ru/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/ru/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | Представляет значения полос ошибок серии для типа значения Custom.<br/>            Только для чтения [`IErrorBarsCustomValues`](/slides/python-net/ru/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/ru/aspose.slides.charts/ichartdatapoint/label/) | Представляет метку точки данных диаграммы.<br/>            Только для чтения [`IDataLabel`](/slides/python-net/ru/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/ru/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | Указывает, что у пузырей применяется 3-D-эффект.<br/>            Чтение/запись **bool**. |
| [`explosion`](/slides/python-net/ru/aspose.slides.charts/ichartdatapoint/explosion/) | Указывает, насколько точка данных должна быть смещена от центра круговой диаграммы.<br/>            Чтение/запись **int**. |
| [`format`](/slides/python-net/ru/aspose.slides.charts/ichartdatapoint/format/) | Представляет свойства форматирования.<br/>            Чтение/запись [`IFormat`](/slides/python-net/ru/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/ru/aspose.slides.charts/ichartdatapoint/marker/) | Указывает маркер данных.<br/>            Только для чтения [`IMarker`](/slides/python-net/ru/aspose.slides.charts/imarker). |
| [`related_legend_entry`](/slides/python-net/ru/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | Свойства соответствующей записи легенды, если тип диаграммы из следующего списка:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Только для чтения [`ILegendEntryProperties`](/slides/python-net/ru/aspose.slides.charts/ilegendentryproperties). |
| [`set_as_total`](/slides/python-net/ru/aspose.slides.charts/ichartdatapoint/set_as_total/) | Устанавливает точку данных как итоговую. Применяется только для серии типа Waterfall. |
| [`invert_if_negative`](/slides/python-net/ru/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | Указывает, что точка данных должна инвертировать свои цвета, если значение отрицательное.<br/>            Чтение/запись **bool**. |
| [`data_point_levels`](/slides/python-net/ru/aspose.slides.charts/ichartdatapoint/data_point_levels/) | Возвращает контейнер уровней точек данных. Применяется для серий Treeamp и Sunburst.<br/>            Индексация уровней точек данных начинается с нуля. |
| [`index`](/slides/python-net/ru/aspose.slides.charts/ichartdatapoint/index/) | Определяет, к какому из дочерних наборов родителя относится эта точка данных.<br/>            Чтение **int**. |
| [`actual_x`](/slides/python-net/ru/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [`actual_y`](/slides/python-net/ru/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [`actual_width`](/slides/python-net/ru/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [`actual_height`](/slides/python-net/ru/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`remove(self)`](/slides/python-net/ru/aspose.slides.charts/ichartdatapoint/remove/#) | Удаляет точку данных из серии диаграммы. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/ru/aspose.slides.charts/ichartdatapoint/get_automatic_data_point_color/#) | Возвращает автоматический цвет точки данных, основанный на индексе серии, индексе точки данных, свойстве ParentSeriesGroup.IsColorVaried и стиле диаграммы. <br/>            Этот цвет используется по умолчанию, если FillType равно NotDefined. |

### См. также
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)