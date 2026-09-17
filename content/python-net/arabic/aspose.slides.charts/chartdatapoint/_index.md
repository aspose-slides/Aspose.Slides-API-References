---
title: ChartDataPoint class
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint فئة

Represents series data point.

The ChartDataPoint type exposes the following members:

## الخصائص

| Property | Description |
| :- | :- |
| [`x_value`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/x_value/) | XValue.<br/>            للقراءة فقط [`IStringOrDoubleChartValue`](/slides/python-net/ar/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/y_value/) | YValue.<br/>            للقراءة فقط [`IDoubleChartValue`](/slides/python-net/ar/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/bubble_size/) | BubbleSize.<br/>            للقراءة فقط [`IDoubleChartValue`](/slides/python-net/ar/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/value/) | Value.<br/>            للقراءة فقط [`IDoubleChartValue`](/slides/python-net/ar/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/size_value/) | إرجاع قيمة الحجم لنقطة بيانات المخطط.<br/>            يُستخدم مع مخططات Treemap و Sunburst.<br/>            للقراءة فقط [`IDoubleChartValue`](/slides/python-net/ar/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/color_value/) | إرجاع قيمة اللون لنقطة بيانات المخطط.<br/>            يُستخدم مع مخططات الخريطة.<br/>            للقراءة فقط [`IDoubleChartValue`](/slides/python-net/ar/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/error_bars_custom_values/) | يمثل قيم أشرطة الأخطاء للسلسلة في حالة نوع القيمة المخصص.<br/>            للقراءة فقط [`IErrorBarsCustomValues`](/slides/python-net/ar/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/label/) | Label.<br/>            للقراءة فقط [`IDataLabel`](/slides/python-net/ar/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/is_bubble_3d/) | يحدد أن الفقاعات لها تأثير ثلاثي الأبعاد يُطبق عليها.<br/>            قراءة/كتابة **bool**. |
| [`explosion`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/explosion/) | يحدد مقدار نقل نقطة البيانات من مركز الفطيرة.<br/>            قراءة/كتابة **int**. |
| [`format`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/format/) | يمثل خصائص التنسيق.<br/>            قراءة/كتابة [`IFormat`](/slides/python-net/ar/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/marker/) | يحدد علامات البيانات.<br/>            للقراءة فقط [`IMarker`](/slides/python-net/ar/aspose.slides.charts/imarker). |
| [`set_as_total`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/set_as_total/) | يضبط نقطة البيانات كإجمالي. يُطبق فقط على نوع السلسلة Waterfall. |
| [`related_legend_entry`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/related_legend_entry/) | خصائص مدخل الأسطورة المقابل في حالة نوع المخطط من القائمة التالية:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            للقراءة فقط [`ILegendEntryProperties`](/slides/python-net/ar/aspose.slides.charts/ilegendentryproperties). |
| [`data_point_levels`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/data_point_levels/) | إرجاع الحاوية لمستويات نقاط البيانات. يُطبق على سلاسل Treeamp و Sunburst.<br/>            فهرسة مستويات نقاط البيانات تبدأ من الصفر. |
| [`index`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/index/) |  |
| [`invert_if_negative`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/invert_if_negative/) | يحدد أن نقطة البيانات ستعكس ألوانها إذا كانت القيمة سلبية.<br/>            قراءة/كتابة **bool**. |
| [`actual_x`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/actual_x/) | يحدد الموضع الفعلي للمحور x (اليسار) لعنصر المخطط بالنسبة إلى الزاوية العلوية اليسرى للمخطط.<br/>            استدعِ الطريقة IChart.ValidateChartLayout() قبل الحصول على القيم الفعلية.<br/>            قراءة **float**. |
| [`actual_y`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/actual_y/) | يحدد أعلى العنصر الفعلي للمخطط بالنسبة إلى الزاوية العلوية اليسرى للمخطط.<br/>            استدعِ الطريقة IChart.ValidateChartLayout() قبل الحصول على القيم الفعلية.<br/>            قراءة **float**. |
| [`actual_width`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/actual_width/) | يحدد العرض الفعلي لعنصر المخطط. استدعِ الطريقة IChart.ValidateChartLayout() قبل الحصول على القيم الفعلية.<br/>            قراءة **float**. |
| [`actual_height`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/actual_height/) | يحدد الارتفاع الفعلي لعنصر المخطط. استدعِ الطريقة IChart.ValidateChartLayout() قبل الحصول على القيم الفعلية.<br/>            قراءة **float**. |

## الطرق

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/remove/#) | يزيل DataPoint من سلسلة المخطط. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/get_automatic_data_point_color/#) | يرجع لونًا تلقائيًا لنقطة البيانات بناءً على فهرس السلسلة، وفهرس نقطة البيانات، وخصيصة ParentSeriesGroup.IsColorVaried، ونمط المخطط.<br/>            يُستخدم هذا اللون افتراضيًا إذا كان FillType يساوي NotDefined. |

### انظر أيضًا
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)