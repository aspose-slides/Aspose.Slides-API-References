---
title: IAxis class
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.charts/iaxis/
---
## IAxis فئة

يُغلف الكائن الذي يمثل محور الرسم البياني.

يعرض نوع IAxis الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`axis_between_categories`](/slides/python-net/ar/aspose.slides.charts/iaxis/axis_between_categories/) | يمثل ما إذا كان محور القيم يتقاطع مع محور الفئات بين الفئات.<br/>            تنطبق هذه الخاصية فقط على محاور الفئات، ولا تنطبق على المخططات الثلاثية الأبعاد.<br/>            قراءة/كتابة **bool**. |
| [`cross_at`](/slides/python-net/ar/aspose.slides.charts/iaxis/cross_at/) | يمثل النقطة على المحور حيث يتقاطع المحور العمودي معه.<br/>            قراءة/كتابة **float**. |
| [`display_unit`](/slides/python-net/ar/aspose.slides.charts/iaxis/display_unit/) | يحدد قيمة المقياس لوحدات العرض لمحور القيم.<br/>            قراءة/كتابة [`DisplayUnitType`](/slides/python-net/ar/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/ar/aspose.slides.charts/iaxis/actual_max_value/) | يحدد القيمة القصوى الفعلية على المحور. استدع طريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية. |
| [`actual_min_value`](/slides/python-net/ar/aspose.slides.charts/iaxis/actual_min_value/) | يحدد القيمة الدنيا الفعلية على المحور. استدع طريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية. |
| [`actual_major_unit`](/slides/python-net/ar/aspose.slides.charts/iaxis/actual_major_unit/) | يحدد الوحدة الرئيسية الفعلية للمحور. استدع طريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية. |
| [`actual_minor_unit`](/slides/python-net/ar/aspose.slides.charts/iaxis/actual_minor_unit/) | يحدد الوحدة الفرعية الفعلية للمحور. استدع طريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية. |
| [`actual_major_unit_scale`](/slides/python-net/ar/aspose.slides.charts/iaxis/actual_major_unit_scale/) | يحدد مقياس الوحدة الرئيسية الفعلية للمحور. استدع طريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية. |
| [`actual_minor_unit_scale`](/slides/python-net/ar/aspose.slides.charts/iaxis/actual_minor_unit_scale/) | يحدد مقياس الوحدة الفرعية الفعلية للمحور. استدع طريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية. |
| [`is_automatic_max_value`](/slides/python-net/ar/aspose.slides.charts/iaxis/is_automatic_max_value/) | يشير إلى ما إذا كانت القيمة القصوى تُعيّن تلقائيًا.<br/>             قراءة/كتابة **bool**. |
| [`max_value`](/slides/python-net/ar/aspose.slides.charts/iaxis/max_value/) | يمثل القيمة القصوى على محور القيم.<br/>             قراءة/كتابة **float**. |
| [`minor_unit`](/slides/python-net/ar/aspose.slides.charts/iaxis/minor_unit/) | يمثل الوحدات الفرعية للتاريخ أو محور القيم.<br/>             قراءة/كتابة **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/ar/aspose.slides.charts/iaxis/is_automatic_minor_unit/) | يشير إلى ما إذا كانت الوحدة الفرعية للمحور تُعيّن تلقائيًا.<br/>             قراءة/كتابة **bool**. |
| [`major_unit`](/slides/python-net/ar/aspose.slides.charts/iaxis/major_unit/) | يمثل الوحدات الرئيسية للتاريخ أو محور القيم.<br/>             قراءة/كتابة **float**. |
| [`is_automatic_major_unit`](/slides/python-net/ar/aspose.slides.charts/iaxis/is_automatic_major_unit/) | يشير إلى ما إذا كانت الوحدة الرئيسية للمحور تُعيّن تلقائيًا.<br/>            قراءة/كتابة **bool**. |
| [`is_automatic_min_value`](/slides/python-net/ar/aspose.slides.charts/iaxis/is_automatic_min_value/) | يشير إلى ما إذا كانت القيمة الدنيا تُعيّن تلقائيًا.<br/>             قراءة/كتابة **bool**. |
| [`min_value`](/slides/python-net/ar/aspose.slides.charts/iaxis/min_value/) | يمثل القيمة الدنيا على محور القيم.<br/>             قراءة/كتابة **float**. |
| [`is_logarithmic`](/slides/python-net/ar/aspose.slides.charts/iaxis/is_logarithmic/) | يمثل ما إذا كان نوع مقياس محور القيم لوغاريتميًا أم لا.<br/>             قراءة/كتابة **bool**. |
| [`log_base`](/slides/python-net/ar/aspose.slides.charts/iaxis/log_base/) | يمثل الأساس اللوغاريتمي. القيمة الافتراضية هي 10.<br/>             قراءة/كتابة **float**. |
| [`is_plot_order_reversed`](/slides/python-net/ar/aspose.slides.charts/iaxis/is_plot_order_reversed/) | يمثل ما إذا كان برنامج MS PowerPoint يرسم نقاط البيانات من الأخير إلى الأول.<br/>             قراءة/كتابة **bool**. |
| [`is_visible`](/slides/python-net/ar/aspose.slides.charts/iaxis/is_visible/) | يمثل ما إذا كان المحور مرئيًا.<br/>             قراءة/كتابة **bool**. |
| [`major_tick_mark`](/slides/python-net/ar/aspose.slides.charts/iaxis/major_tick_mark/) | يمثل نوع علامة الفاصل الرئيسية للمحور المحدد.<br/>             قراءة/كتابة [`TickMarkType`](/slides/python-net/ar/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/ar/aspose.slides.charts/iaxis/minor_tick_mark/) | يمثل نوع علامة الفاصل الفرعية للمحور المحدد.<br/>             قراءة/كتابة [`TickMarkType`](/slides/python-net/ar/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/ar/aspose.slides.charts/iaxis/tick_label_position/) | يمثل موضع تسميات علامات الفاصل على المحور المحدد.<br/>             قراءة/كتابة [`TickLabelPositionType`](/slides/python-net/ar/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/ar/aspose.slides.charts/iaxis/major_unit_scale/) | يمثل مقياس الوحدة الرئيسية لمحور التاريخ.<br/>             قراءة/كتابة [`TimeUnitType`](/slides/python-net/ar/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/ar/aspose.slides.charts/iaxis/minor_unit_scale/) | يمثل مقياس الوحدة الرئيسية لمحور التاريخ.<br/>             قراءة/كتابة [`TimeUnitType`](/slides/python-net/ar/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/ar/aspose.slides.charts/iaxis/base_unit_scale/) | يحدد أصغر وحدة زمنية ممثلة على محور التاريخ.<br/>            قراءة/كتابة [`TimeUnitType`](/slides/python-net/ar/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/ar/aspose.slides.charts/iaxis/minor_grid_lines_format/) | يمثل تنسيق خطوط الشبكة الفرعية على محور الرسم البياني.<br/>             قراءة فقط [`IChartLinesFormat`](/slides/python-net/ar/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/ar/aspose.slides.charts/iaxis/major_grid_lines_format/) | يمثل تنسيق خطوط الشبكة الرئيسية على محور الرسم البياني.<br/>             قراءة فقط [`IChartLinesFormat`](/slides/python-net/ar/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/ar/aspose.slides.charts/iaxis/show_minor_grid_lines/) | يمثل ما إذا كانت خطوط الشبكة الفرعية مُظهرة.<br/>             قراءة فقط **bool**. |
| [`show_major_grid_lines`](/slides/python-net/ar/aspose.slides.charts/iaxis/show_major_grid_lines/) | يمثل ما إذا كانت خطوط الشبكة الرئيسية مُظهرة.<br/>             قراءة فقط **bool**. |
| [`format`](/slides/python-net/ar/aspose.slides.charts/iaxis/format/) | يمثل تنسيق المحور.<br/>             قراءة فقط [`IAxisFormat`](/slides/python-net/ar/aspose.slides.charts/iaxisformat). |
| [`title`](/slides/python-net/ar/aspose.slides.charts/iaxis/title/) | يحصل على عنوان المحور.<br/>             قراءة فقط [`IChartTitle`](/slides/python-net/ar/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/ar/aspose.slides.charts/iaxis/cross_type/) | يمثل نوع التقاطع على المحور المحدد حيث يتقاطع المحور الآخر.<br/>             قراءة/كتابة [`CrossesType`](/slides/python-net/ar/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/ar/aspose.slides.charts/iaxis/position/) | يمثل موضع المحور.<br/>             قراءة/كتابة [`AxisPositionType`](/slides/python-net/ar/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/ar/aspose.slides.charts/iaxis/has_title/) | يحدد ما إذا كان للمحور عنوان مرئي.<br/>            قراءة/كتابة **bool**. |
| [`number_format`](/slides/python-net/ar/aspose.slides.charts/iaxis/number_format/) | يمثل سلسلة التنسيق لتسميات المحور.<br/>            قراءة/كتابة **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/ar/aspose.slides.charts/iaxis/is_number_format_linked_to_source/) | يشير إلى ما إذا كان التنسيق مرتبطًا ببيانات المصدر.<br/>            قراءة/كتابة **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/ar/aspose.slides.charts/iaxis/tick_label_rotation_angle/) | يمثل زاوية دوران تسميات العلامات.<br/>            قراءة/كتابة **float**. |
| [`tick_label_spacing`](/slides/python-net/ar/aspose.slides.charts/iaxis/tick_label_spacing/) | يحدد عدد تسميات العلامات التي يتم تخطيها بين كل تسمية مرسومة.<br/>            قراءة/كتابة **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/ar/aspose.slides.charts/iaxis/is_automatic_tick_label_spacing/) | يحدد قيمة التباعد التلقائي لتسميات العلامات. إذا كان false: استخدم خاصية TickLabelSpacing.<br/>            قراءة/كتابة **bool**. |
| [`tick_marks_spacing`](/slides/python-net/ar/aspose.slides.charts/iaxis/tick_marks_spacing/) | يحدد عدد علامات الفاصل التي يجب تخطيها قبل أن يتم <br/>            رسم العلامة التالية. يُطبق على محور الفئة أو المحور المتسلسل.<br/>            قراءة/كتابة **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/ar/aspose.slides.charts/iaxis/is_automatic_tick_marks_spacing/) | يحدد قيمة التباعد التلقائي لعلامات الفاصل. إذا كان false: استخدم خاصية TickMarksSpacing.<br/>            قراءة/كتابة **bool**. |
| [`label_offset`](/slides/python-net/ar/aspose.slides.charts/iaxis/label_offset/) | يحدد المسافة بين التسميات والمحور. يُطبق على محور الفئة أو التاريخ. يجب أن تكون القيمة بين 0% و 1000%.<br/>            قراءة/كتابة **int**. |
| [`category_axis_type`](/slides/python-net/ar/aspose.slides.charts/iaxis/category_axis_type/) | يحدد نوع محور الفئة.<br/>            قراءة/كتابة [`IAxis.category_axis_type`](/slides/python-net/ar/aspose.slides.charts/iaxis/category_axis_type). |
| [`aggregation_type`](/slides/python-net/ar/aspose.slides.charts/iaxis/aggregation_type/) | يمثل نوع التجميع لمحور الفئة (تجميع). يُطبق على الفئة. يُستخدم مع سلسلة Histogram أو HistogramPareto فقط. |
| [`bin_width`](/slides/python-net/ar/aspose.slides.charts/iaxis/bin_width/) | يحدد عرض الصندوق عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByBinWidth.<br/>            يُطبق على محاور الفئة. يُستخدم مع سلسلة Histogram أو HistogramPareto فقط. |
| [`number_of_bins`](/slides/python-net/ar/aspose.slides.charts/iaxis/number_of_bins/) | يحدد عدد الصناديق عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByNumberOfBins.<br/>            يُطبق على محاور الفئة. يُستخدم مع سلسلة Histogram أو HistogramPareto فقط. |
| [`is_overflow_bin`](/slides/python-net/ar/aspose.slides.charts/iaxis/is_overflow_bin/) | يحدد ما إذا تم تطبيق صندوق الفائض. استخدم IsAutomaticOverflowBin و OverflowBin لضبط قيمة صندوق الفائض. |
| [`is_automatic_overflow_bin`](/slides/python-net/ar/aspose.slides.charts/iaxis/is_automatic_overflow_bin/) | يحدد قيمة صندوق الفائض التلقائي. إذا كان false: استخدم خاصية OverflowBin. |
| [`overflow_bin`](/slides/python-net/ar/aspose.slides.charts/iaxis/overflow_bin/) | يحدد قيمة مخصصة لصندوق الفائض. يُطبق عندما تكون خاصية IsAutomaticOverflowBin مضبوطة على false وتكون خاصية IsOverflowBin مساوية true. |
| [`is_underflow_bin`](/slides/python-net/ar/aspose.slides.charts/iaxis/is_underflow_bin/) | يحدد ما إذا تم تطبيق صندوق النقص. استخدم IsAutomaticUnderflowBin و UnderflowBin لضبط قيمة صندوق النقص. |
| [`is_automatic_underflow_bin`](/slides/python-net/ar/aspose.slides.charts/iaxis/is_automatic_underflow_bin/) | يحدد قيمة صندوق النقص التلقائي. إذا كان false: استخدم خاصية UnderflowBin. |
| [`underflow_bin`](/slides/python-net/ar/aspose.slides.charts/iaxis/underflow_bin/) | يحدد قيمة مخصصة لصندوق النقص. يُطبق عندما تكون خاصية IsAutomaticUnderflowBin مضبوطة على false وتكون خاصية IsUnderflowBin مساوية true. |
| [`text_format`](/slides/python-net/ar/aspose.slides.charts/iaxis/text_format/) |  |
| [`chart`](/slides/python-net/ar/aspose.slides.charts/iaxis/chart/) |  |
| [`slide`](/slides/python-net/ar/aspose.slides.charts/iaxis/slide/) |  |
| [`presentation`](/slides/python-net/ar/aspose.slides.charts/iaxis/presentation/) |  |

## الأساليب

| الطريقة | الوصف |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/ar/aspose.slides.charts/iaxis/set_category_axis_type_automatically/#) | يضبط خاصية IAxis.CategoryAxisType بقيمة يتم تحديدها تلقائيًا بناءً على بيانات المحور. |

### انظر أيضًا
* وحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* مكتبة [`Aspose.Slides`](/slides/python-net)