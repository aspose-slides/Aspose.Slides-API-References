---
title: IAxis class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/iaxis/
---
## IAxis класс

Инкапсулирует объект, представляющий ось диаграммы.

Тип IAxis предоставляет следующие члены:

## Свойства

| Property | Description |
| :- | :- |
| [`axis_between_categories`](/slides/python-net/ru/aspose.slides.charts/iaxis/axis_between_categories/) | Представляет, пересекает ли ось значений ось категорий между категориями.<br/>            Это свойство применяется только к осям категорий и не применяется к 3-D диаграммам.<br/>            Чтение/запись **bool**. |
| [`cross_at`](/slides/python-net/ru/aspose.slides.charts/iaxis/cross_at/) | Представляет точку на оси, где перпендикулярная ось пересекает её.<br/>            Чтение/запись **float**. |
| [`display_unit`](/slides/python-net/ru/aspose.slides.charts/iaxis/display_unit/) | Указывает значение масштабирования единиц отображения для оси значений.<br/>            Чтение/запись [`DisplayUnitType`](/slides/python-net/ru/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/ru/aspose.slides.charts/iaxis/actual_max_value/) | Указывает фактическое максимальное значение на оси. Сначала вызовите метод IChart.ValidateChartLayout() для получения фактического значения. |
| [`actual_min_value`](/slides/python-net/ru/aspose.slides.charts/iaxis/actual_min_value/) | Указывает фактическое минимальное значение на оси. Сначала вызовите метод IChart.ValidateChartLayout() для получения фактического значения. |
| [`actual_major_unit`](/slides/python-net/ru/aspose.slides.charts/iaxis/actual_major_unit/) | Указывает фактическую основную единицу оси. Сначала вызовите метод IChart.ValidateChartLayout() для получения фактического значения. |
| [`actual_minor_unit`](/slides/python-net/ru/aspose.slides.charts/iaxis/actual_minor_unit/) | Указывает фактическую второстепенную единицу оси. Сначала вызовите метод IChart.ValidateChartLayout() для получения фактического значения. |
| [`actual_major_unit_scale`](/slides/python-net/ru/aspose.slides.charts/iaxis/actual_major_unit_scale/) | Указывает фактический масштаб основной единицы оси. Сначала вызовите метод IChart.ValidateChartLayout() для получения фактического значения. |
| [`actual_minor_unit_scale`](/slides/python-net/ru/aspose.slides.charts/iaxis/actual_minor_unit_scale/) | Указывает фактический масштаб второстепенной единицы оси. Сначала вызовите метод IChart.ValidateChartLayout() для получения фактического значения. |
| [`is_automatic_max_value`](/slides/python-net/ru/aspose.slides.charts/iaxis/is_automatic_max_value/) | Указывает, назначено ли максимальное значение автоматически.<br/>             Чтение/запись **bool**. |
| [`max_value`](/slides/python-net/ru/aspose.slides.charts/iaxis/max_value/) | Представляет максимальное значение на оси значений.<br/>             Чтение/запись **float**. |
| [`minor_unit`](/slides/python-net/ru/aspose.slides.charts/iaxis/minor_unit/) | Представляет второстепенные единицы для оси даты или значений.<br/>             Чтение/запись **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/ru/aspose.slides.charts/iaxis/is_automatic_minor_unit/) | Указывает, назначена ли второстепенная единица оси автоматически.<br/>             Чтение/запись **bool**. |
| [`major_unit`](/slides/python-net/ru/aspose.slides.charts/iaxis/major_unit/) | Представляет основные единицы для оси даты или значений.<br/>             Чтение/запись **float**. |
| [`is_automatic_major_unit`](/slides/python-net/ru/aspose.slides.charts/iaxis/is_automatic_major_unit/) | Указывает, назначена ли основная единица оси автоматически.<br/>            Чтение/запись **bool**. |
| [`is_automatic_min_value`](/slides/python-net/ru/aspose.slides.charts/iaxis/is_automatic_min_value/) | Указывает, назначено ли минимальное значение автоматически.<br/>             Чтение/запись **bool**. |
| [`min_value`](/slides/python-net/ru/aspose.slides.charts/iaxis/min_value/) | Представляет минимальное значение на оси значений.<br/>             Чтение/запись **float**. |
| [`is_logarithmic`](/slides/python-net/ru/aspose.slides.charts/iaxis/is_logarithmic/) | Указывает, является ли тип шкалы оси значений логарифмическим.<br/>             Чтение/запись **bool**. |
| [`log_base`](/slides/python-net/ru/aspose.slides.charts/iaxis/log_base/) | Представляет основание логарифма. Значение по умолчанию — 10.<br/>             Чтение/запись **float**. |
| [`is_plot_order_reversed`](/slides/python-net/ru/aspose.slides.charts/iaxis/is_plot_order_reversed/) | Указывает, отображает ли MS PowerPoint точки данных от последней к первой.<br/>             Чтение/запись **bool**. |
| [`is_visible`](/slides/python-net/ru/aspose.slides.charts/iaxis/is_visible/) | Указывает, видима ли ось.<br/>             Чтение/запись **bool**. |
| [`major_tick_mark`](/slides/python-net/ru/aspose.slides.charts/iaxis/major_tick_mark/) | Представляет тип основной метки деления для указанной оси.<br/>             Чтение/запись [`TickMarkType`](/slides/python-net/ru/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/ru/aspose.slides.charts/iaxis/minor_tick_mark/) | Представляет тип второстепенной метки деления для указанной оси.<br/>             Чтение/запись [`TickMarkType`](/slides/python-net/ru/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/ru/aspose.slides.charts/iaxis/tick_label_position/) | Представляет позицию меток делений на указанной оси.<br/>             Чтение/запись [`TickLabelPositionType`](/slides/python-net/ru/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/ru/aspose.slides.charts/iaxis/major_unit_scale/) | Представляет масштаб основной единицы для оси даты.<br/>             Чтение/запись [`TimeUnitType`](/slides/python-net/ru/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/ru/aspose.slides.charts/iaxis/minor_unit_scale/) | Представляет масштаб основной единицы для оси даты.<br/>             Чтение/запись [`TimeUnitType`](/slides/python-net/ru/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/ru/aspose.slides.charts/iaxis/base_unit_scale/) | Указывает наименьшую единицу времени, представленную на оси даты.<br/>            Чтение/запись [`TimeUnitType`](/slides/python-net/ru/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/ru/aspose.slides.charts/iaxis/minor_grid_lines_format/) | Представляет формат второстепенных линий сетки на оси диаграммы.<br/>             Только чтение [`IChartLinesFormat`](/slides/python-net/ru/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/ru/aspose.slides.charts/iaxis/major_grid_lines_format/) | Представляет формат основных линий сетки на оси диаграммы.<br/>             Только чтение [`IChartLinesFormat`](/slides/python-net/ru/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/ru/aspose.slides.charts/iaxis/show_minor_grid_lines/) | Указывает, отображаются ли второстепенные линии сетки.<br/>             Только чтение **bool**. |
| [`show_major_grid_lines`](/slides/python-net/ru/aspose.slides.charts/iaxis/show_major_grid_lines/) | Указывает, отображаются ли основные линии сетки.<br/>             Только чтение **bool**. |
| [`format`](/slides/python-net/ru/aspose.slides.charts/iaxis/format/) | Представляет формат оси.<br/>             Только чтение [`IAxisFormat`](/slides/python-net/ru/aspose.slides.charts/iaxisformat). |
| [`title`](/slides/python-net/ru/aspose.slides.charts/iaxis/title/) | Получает заголовок оси.<br/>             Только чтение [`IChartTitle`](/slides/python-net/ru/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/ru/aspose.slides.charts/iaxis/cross_type/) | Представляет тип пересечения (CrossType) на указанной оси, где другая ось её пересекает.<br/>             Чтение/запись [`CrossesType`](/slides/python-net/ru/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/ru/aspose.slides.charts/iaxis/position/) | Представляет позицию оси.<br/>             Чтение/запись [`AxisPositionType`](/slides/python-net/ru/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/ru/aspose.slides.charts/iaxis/has_title/) | Определяет, имеет ли ось видимый заголовок.<br/>            Чтение/запись **bool**. |
| [`number_format`](/slides/python-net/ru/aspose.slides.charts/iaxis/number_format/) | Представляет строку формата для подписей оси.<br/>            Чтение/запись **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/ru/aspose.slides.charts/iaxis/is_number_format_linked_to_source/) | Указывает, связан ли формат с исходными данными.<br/>            Чтение/запись **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/ru/aspose.slides.charts/iaxis/tick_label_rotation_angle/) | Представляет угол вращения меток делений<br/>            Чтение/запись **float**. |
| [`tick_label_spacing`](/slides/python-net/ru/aspose.slides.charts/iaxis/tick_label_spacing/) | Указывает количество меток делений, которые следует пропустить между отрисованными метками.<br/>            Чтение/запись **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/ru/aspose.slides.charts/iaxis/is_automatic_tick_label_spacing/) | Указывает значение автоматического интервала между метками делений. Если false: используйте свойство TickLabelSpacing.<br/>            Чтение/запись **bool**. |
| [`tick_marks_spacing`](/slides/python-net/ru/aspose.slides.charts/iaxis/tick_marks_spacing/) | Указывает, сколько меток делений следует пропустить перед следующей <br/>            отрисовкой. Применяется к оси категории или серии.<br/>            Чтение/запись **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/ru/aspose.slides.charts/iaxis/is_automatic_tick_marks_spacing/) | Указывает значение автоматического интервала между метками делений. Если false: используйте свойство TickMarksSpacing.<br/>            Чтение/запись **bool**. |
| [`label_offset`](/slides/python-net/ru/aspose.slides.charts/iaxis/label_offset/) | Указывает расстояние меток от оси. Применяется к оси категории или даты. Значение должно быть от 0% до 1000%.<br/>            Чтение/запись **int**. |
| [`category_axis_type`](/slides/python-net/ru/aspose.slides.charts/iaxis/category_axis_type/) | Указывает тип оси категории.<br/>            Чтение/запись [`IAxis.category_axis_type`](/slides/python-net/ru/aspose.slides.charts/iaxis/category_axis_type). |
| [`aggregation_type`](/slides/python-net/ru/aspose.slides.charts/iaxis/aggregation_type/) | Представляет тип агрегации оси категории (биннинг). Применяется к категории. Используется только с сериями Histogram или HistogramPareto. |
| [`bin_width`](/slides/python-net/ru/aspose.slides.charts/iaxis/bin_width/) | Указывает ширину бина, когда значение свойства AggregationType установлено в AxisAggregationType.ByBinWidth.<br/>            Применяется к осям категорий. Используется только с сериями Histogram или HistogramPareto. |
| [`number_of_bins`](/slides/python-net/ru/aspose.slides.charts/iaxis/number_of_bins/) | Указывает количество бинов, когда значение свойства AggregationType установлено в AxisAggregationType.ByNumberOfBins.<br/>            Применяется к осям категорий. Используется только с сериями Histogram или HistogramPareto. |
| [`is_overflow_bin`](/slides/python-net/ru/aspose.slides.charts/iaxis/is_overflow_bin/) | Указывает, применяется ли переполненный бин. Используйте IsAutomaticOverflowBin и OverflowBin для настройки значения переполненного бина. |
| [`is_automatic_overflow_bin`](/slides/python-net/ru/aspose.slides.charts/iaxis/is_automatic_overflow_bin/) | Указывает значение автоматического переполненного бина. Если false: используйте свойство OverflowBin. |
| [`overflow_bin`](/slides/python-net/ru/aspose.slides.charts/iaxis/overflow_bin/) | Указывает пользовательское значение переполненного бина. Применяется, когда свойство IsAutomaticOverflowBin установлено в false и свойство IsOverflowBin равно true. |
| [`is_underflow_bin`](/slides/python-net/ru/aspose.slides.charts/iaxis/is_underflow_bin/) | Указывает, применяется ли недополненный бин. Используйте IsAutomaticUnderflowBin и UnderflowBin для настройки значения недополненного бина. |
| [`is_automatic_underflow_bin`](/slides/python-net/ru/aspose.slides.charts/iaxis/is_automatic_underflow_bin/) | Указывает значение автоматического недополненного бина. Если false: используйте свойство UnderflowBin. |
| [`underflow_bin`](/slides/python-net/ru/aspose.slides.charts/iaxis/underflow_bin/) | Указывает пользовательское значение недополненного бина. Применяется, когда свойство IsAutomaticUnderflowBin установлено в false и свойство IsUnderflowBin равно true. |
| [`text_format`](/slides/python-net/ru/aspose.slides.charts/iaxis/text_format/) |  |
| [`chart`](/slides/python-net/ru/aspose.slides.charts/iaxis/chart/) |  |
| [`slide`](/slides/python-net/ru/aspose.slides.charts/iaxis/slide/) |  |
| [`presentation`](/slides/python-net/ru/aspose.slides.charts/iaxis/presentation/) |  |

## Методы

| Method | Description |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/ru/aspose.slides.charts/iaxis/set_category_axis_type_automatically/#) | Устанавливает свойство IAxis.CategoryAxisType значением, автоматически определяемым на основе данных оси. |

### См. также
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)