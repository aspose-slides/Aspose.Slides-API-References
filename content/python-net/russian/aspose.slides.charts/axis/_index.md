---
title: Axis class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/axis/
---
## Axis класс

Инкапсулирует объект, представляющий ось диаграммы.

Тип Axis раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`chart`](/slides/python-net/ru/aspose.slides.charts/axis/chart/) | Возвращает родительскую диаграмму.<br/>            Только для чтения [`IChart`](/slides/python-net/ru/aspose.slides.charts/ichart). |
| [`axis_between_categories`](/slides/python-net/ru/aspose.slides.charts/axis/axis_between_categories/) | Указывает, пересекает ли ось значений ось категорий между категориями.<br/>             Это свойство применяется только к осям категорий и не действует для 3-D диаграмм.<br/>             Чтение/запись **bool**. |
| [`category_axis_type`](/slides/python-net/ru/aspose.slides.charts/axis/category_axis_type/) | Определяет тип оси категорий.<br/>            Чтение/запись [`CategoryAxisType`](/slides/python-net/ru/aspose.slides.charts/categoryaxistype). |
| [`cross_at`](/slides/python-net/ru/aspose.slides.charts/axis/cross_at/) | Представляет точку на оси, где перпендикулярная ось пересекает её.<br/>             Чтение/запись **float**. |
| [`display_unit`](/slides/python-net/ru/aspose.slides.charts/axis/display_unit/) | Задает значение масштабирования единиц отображения для оси значений.<br/>             Чтение/запись [`DisplayUnitType`](/slides/python-net/ru/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/ru/aspose.slides.charts/axis/actual_max_value/) | Задает фактическое максимальное значение на оси. Сначала вызовите метод IChart.ValidateChartLayout(), чтобы получить фактическое значение. |
| [`actual_min_value`](/slides/python-net/ru/aspose.slides.charts/axis/actual_min_value/) | Задает фактическое минимальное значение на оси. Сначала вызовите метод IChart.ValidateChartLayout(), чтобы получить фактическое значение. |
| [`actual_major_unit`](/slides/python-net/ru/aspose.slides.charts/axis/actual_major_unit/) | Задает фактическую основную единицу оси. Сначала вызовите метод IChart.ValidateChartLayout(), чтобы получить фактическое значение. |
| [`actual_minor_unit`](/slides/python-net/ru/aspose.slides.charts/axis/actual_minor_unit/) | Задает фактическую вспомогательную единицу оси. Сначала вызовите метод IChart.ValidateChartLayout(), чтобы получить фактическое значение. |
| [`actual_major_unit_scale`](/slides/python-net/ru/aspose.slides.charts/axis/actual_major_unit_scale/) | Задает фактический масштаб основной единицы оси. Сначала вызовите метод IChart.ValidateChartLayout(), чтобы получить фактическое значение. |
| [`actual_minor_unit_scale`](/slides/python-net/ru/aspose.slides.charts/axis/actual_minor_unit_scale/) | Задает фактический масштаб вспомогательной единицы оси. Сначала вызовите метод IChart.ValidateChartLayout(), чтобы получить фактическое значение. |
| [`is_automatic_max_value`](/slides/python-net/ru/aspose.slides.charts/axis/is_automatic_max_value/) | Указывает, назначается ли максимальное значение автоматически.<br/>             Чтение/запись **bool**. |
| [`max_value`](/slides/python-net/ru/aspose.slides.charts/axis/max_value/) | Представляет максимальное значение на оси значений.<br/>             Чтение/запись **float**. |
| [`minor_unit`](/slides/python-net/ru/aspose.slides.charts/axis/minor_unit/) | Представляет вспомогательные единицы для оси даты или значений.<br/>             Чтение/запись **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/ru/aspose.slides.charts/axis/is_automatic_minor_unit/) | Указывает, назначается ли вспомогательная единица оси автоматически.<br/>             Чтение/запись **bool**. |
| [`major_unit`](/slides/python-net/ru/aspose.slides.charts/axis/major_unit/) | Представляет основные единицы для оси даты или значений.<br/>             Чтение/запись **float**. |
| [`is_automatic_major_unit`](/slides/python-net/ru/aspose.slides.charts/axis/is_automatic_major_unit/) | Указывает, назначается ли основная единица оси автоматически. <br/>            Чтение/запись **bool**. |
| [`is_automatic_min_value`](/slides/python-net/ru/aspose.slides.charts/axis/is_automatic_min_value/) | Указывает, назначается ли минимальное значение автоматически.<br/>             Чтение/запись **bool**. |
| [`min_value`](/slides/python-net/ru/aspose.slides.charts/axis/min_value/) | Представляет минимальное значение на оси значений.<br/>             Чтение/запись **float**. |
| [`is_logarithmic`](/slides/python-net/ru/aspose.slides.charts/axis/is_logarithmic/) | Указывает, является ли тип шкалы оси значений логарифмическим.<br/>             Чтение/запись **bool**. |
| [`log_base`](/slides/python-net/ru/aspose.slides.charts/axis/log_base/) | Представляет основание логарифма. Значение по умолчанию — 10.<br/>             Чтение/запись **float**. |
| [`is_plot_order_reversed`](/slides/python-net/ru/aspose.slides.charts/axis/is_plot_order_reversed/) | Указывает, выводит ли MS PowerPoint точки данных от последней к первой.<br/>             Чтение/запись **bool**. |
| [`is_visible`](/slides/python-net/ru/aspose.slides.charts/axis/is_visible/) | Указывает, видна ли ось.<br/>             Чтение/запись **bool**. |
| [`major_tick_mark`](/slides/python-net/ru/aspose.slides.charts/axis/major_tick_mark/) | Представляет тип основной метки деления для указанной оси.<br/>             Чтение/запись [`TickMarkType`](/slides/python-net/ru/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/ru/aspose.slides.charts/axis/minor_tick_mark/) | Представляет тип вспомогательной метки деления для указанной оси.<br/>             Чтение/запись [`TickMarkType`](/slides/python-net/ru/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/ru/aspose.slides.charts/axis/tick_label_position/) | Представляет положение меток делений на указанной оси.<br/>             Чтение/запись [`TickLabelPositionType`](/slides/python-net/ru/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/ru/aspose.slides.charts/axis/major_unit_scale/) | Представляет масштаб основной единицы для оси даты.<br/>             Чтение/запись [`TimeUnitType`](/slides/python-net/ru/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/ru/aspose.slides.charts/axis/minor_unit_scale/) | Представляет масштаб основной единицы для оси даты.<br/>             Чтение/запись [`TimeUnitType`](/slides/python-net/ru/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/ru/aspose.slides.charts/axis/base_unit_scale/) | Задает наименьшую единицу времени, отображаемую на оси даты.<br/>            Чтение/запись [`TimeUnitType`](/slides/python-net/ru/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/ru/aspose.slides.charts/axis/minor_grid_lines_format/) | Представляет формат вспомогательных сеток на оси диаграммы.<br/>             Только для чтения [`IChartLinesFormat`](/slides/python-net/ru/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/ru/aspose.slides.charts/axis/major_grid_lines_format/) | Представляет формат основных сеток на оси диаграммы.<br/>             Только для чтения [`IChartLinesFormat`](/slides/python-net/ru/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/ru/aspose.slides.charts/axis/show_minor_grid_lines/) | Чтобы скрыть вспомогательную сетку, задайте MinorGridLinesFormat.Line.FillFormat.FillType = FillType.NoFill.<br/>            Только для чтения **bool**. |
| [`show_major_grid_lines`](/slides/python-net/ru/aspose.slides.charts/axis/show_major_grid_lines/) | Чтобы скрыть основную сетку, задайте MajorGridLinesFormat.Line.FillFormat.FillType = FillType.NoFill.<br/>            Только для чтения **bool**. |
| [`format`](/slides/python-net/ru/aspose.slides.charts/axis/format/) | Представляет формат оси.<br/>             Только для чтения [`IAxisFormat`](/slides/python-net/ru/aspose.slides.charts/iaxisformat). |
| [`text_format`](/slides/python-net/ru/aspose.slides.charts/axis/text_format/) | Представляет формат текста.<br/>             Только для чтения [`IChartTextFormat`](/slides/python-net/ru/aspose.slides.charts/icharttextformat). |
| [`title`](/slides/python-net/ru/aspose.slides.charts/axis/title/) | Получает заголовок оси.<br/>             Только для чтения [`IChartTitle`](/slides/python-net/ru/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/ru/aspose.slides.charts/axis/cross_type/) | Представляет CrossType на указанной оси, где она пересекает другую ось.<br/>             Чтение/запись [`CrossesType`](/slides/python-net/ru/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/ru/aspose.slides.charts/axis/position/) | Представляет позицию оси.<br/>             Чтение/запись [`AxisPositionType`](/slides/python-net/ru/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/ru/aspose.slides.charts/axis/has_title/) | Определяет, имеет ли ось видимый заголовок.<br/>            Чтение/запись **bool**. |
| [`number_format`](/slides/python-net/ru/aspose.slides.charts/axis/number_format/) | Представляет строку формата для подписей оси.<br/>            Чтение/запись **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/ru/aspose.slides.charts/axis/is_number_format_linked_to_source/) | Указывает, является ли формат связанным с исходными данными.<br/>            Чтение/запись **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/ru/aspose.slides.charts/axis/tick_label_rotation_angle/) | Представляет угол поворота подписей делений.<br/>            Чтение/запись **float**. |
| [`tick_label_spacing`](/slides/python-net/ru/aspose.slides.charts/axis/tick_label_spacing/) | Задает, сколько подписей делений пропускать между отрисованными метками. Применяется к осям категорий или рядов.<br/>            Чтение/запись **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/ru/aspose.slides.charts/axis/is_automatic_tick_label_spacing/) | Задает автоматическое значение интервала подписей делений. Если false: используйте свойство TickLabelSpacing.<br/>            Чтение/запись **bool**. |
| [`tick_marks_spacing`](/slides/python-net/ru/aspose.slides.charts/axis/tick_marks_spacing/) | Задает, сколько делений пропустить перед следующей отрисовкой.<br/>            Применяется к осям категорий или рядов.<br/>            Чтение/запись **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/ru/aspose.slides.charts/axis/is_automatic_tick_marks_spacing/) | Задает автоматическое значение интервала делений. Если false: используйте свойство TickMarksSpacing.<br/>            Чтение/запись **bool**. |
| [`label_offset`](/slides/python-net/ru/aspose.slides.charts/axis/label_offset/) | Задает расстояние подписей от оси. Применяется к осям категорий или дат. Значение должно быть от 0 % до 1000 %.<br/>            Чтение/запись **int**. |
| [`aggregation_type`](/slides/python-net/ru/aspose.slides.charts/axis/aggregation_type/) | Представляет тип агрегации оси категорий (биннинг). Применяется к категориям. Используется только с рядами Histogram или HistogramPareto. |
| [`bin_width`](/slides/python-net/ru/aspose.slides.charts/axis/bin_width/) | Задает ширину бина, когда свойство AggregationType установлено в AxisAggregationType.ByBinWidth.<br/>            Применяется к осям категорий. Используется только с рядами Histogram или HistogramPareto. |
| [`number_of_bins`](/slides/python-net/ru/aspose.slides.charts/axis/number_of_bins/) | Задает количество бин, когда свойство AggregationType установлено в AxisAggregationType.ByNumberOfBins.<br/>            Применяется к осям категорий. Используется только с рядами Histogram или HistogramPareto. |
| [`is_overflow_bin`](/slides/python-net/ru/aspose.slides.charts/axis/is_overflow_bin/) | Указывает, применяется ли переполненный бин. Используйте IsAutomaticOverflowBin и OverflowBin для настройки значения переполненного бина. |
| [`is_automatic_overflow_bin`](/slides/python-net/ru/aspose.slides.charts/axis/is_automatic_overflow_bin/) | Указывает автоматическое значение переполненного бина. Если false: используйте свойство OverflowBin. |
| [`overflow_bin`](/slides/python-net/ru/aspose.slides.charts/axis/overflow_bin/) | Задает пользовательское значение переполненного бина. Применяется, когда свойство IsAutomaticOverflowBin установлено в false и IsOverflowBin равно true. |
| [`is_underflow_bin`](/slides/python-net/ru/aspose.slides.charts/axis/is_underflow_bin/) | Указывает, применяется ли недостаточный бин. Используйте IsAutomaticUnderflowBin и UnderflowBin для настройки значения недостаточного бина. |
| [`is_automatic_underflow_bin`](/slides/python-net/ru/aspose.slides.charts/axis/is_automatic_underflow_bin/) | Указывает автоматическое значение недостаточного бина. Если false: используйте свойство UnderflowBin. |
| [`underflow_bin`](/slides/python-net/ru/aspose.slides.charts/axis/underflow_bin/) | Задает пользовательское значение недостаточного бина. Применяется, когда свойство IsAutomaticUnderflowBin установлено в false и IsUnderflowBin равно true. |
| [`slide`](/slides/python-net/ru/aspose.slides.charts/axis/slide/) |  |
| [`presentation`](/slides/python-net/ru/aspose.slides.charts/axis/presentation/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/ru/aspose.slides.charts/axis/set_category_axis_type_automatically/#) | Устанавливает свойство IAxis.CategoryAxisType значением, автоматически определяемым на основе данных оси. |


### См. также
* module [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)