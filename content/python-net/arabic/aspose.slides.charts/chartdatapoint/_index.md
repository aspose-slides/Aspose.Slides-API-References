---
title: ChartDataPoint class
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint فئة

يمثل نقطة بيانات السلسلة.

نوع ChartDataPoint يعرض الأعضاء التالية:

## الخصائص

| Property | Description |
| :- | :- |
| [`x_value`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/x_value/) | XValue.<br/>            قراءة فقط [`IStringOrDoubleChartValue`](/slides/python-net/ar/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/y_value/) | YValue.<br/>            قراءة فقط [`IDoubleChartValue`](/slides/python-net/ar/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/bubble_size/) | BubbleSize.<br/>            قراءة فقط [`IDoubleChartValue`](/slides/python-net/ar/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/value/) | Value.<br/>            قراءة فقط [`IDoubleChartValue`](/slides/python-net/ar/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/size_value/) | يعيد قيمة الحجم لنقطة بيانات المخطط.<br/>            يستخدم مع مخططات Treemap و Sunburst. <br/>            قراءة فقط [`IDoubleChartValue`](/slides/python-net/ar/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/color_value/) | يعيد قيمة اللون لنقطة بيانات المخطط.<br/>            يستخدم مع مخططات Map. <br/>            قراءة فقط [`IDoubleChartValue`](/slides/python-net/ar/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/error_bars_custom_values/) | يمثل قيم أشرطة الخطأ للسلسلة في حالة نوع القيمة Custom.<br/>            قراءة فقط [`IErrorBarsCustomValues`](/slides/python-net/ar/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/label/) | Label.<br/>            قراءة فقط [`IDataLabel`](/slides/python-net/ar/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/is_bubble_3d/) | يحدد أن الفقاعات لها تأثير ثلاثي الأبعاد مطبق عليها.<br/>            قراءة/كتابة **bool**. |
| [`explosion`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/explosion/) | يحدد مقدار تحريك نقطة البيانات من مركز الفطيرة.<br/>            قراءة/كتابة **int**. |
| [`format`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/format/) | يمثل خصائص التنسيق.<br/>            قراءة/كتابة [`IFormat`](/slides/python-net/ar/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/marker/) | يحدد علامة البيانات.<br/>            قراءة فقط [`IMarker`](/slides/python-net/ar/aspose.slides.charts/imarker). |
| [`set_as_total`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/set_as_total/) | يضبط نقطة البيانات كإجمالي. يُطبق فقط على نوع السلسلة Waterfall. |
| [`related_legend_entry`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/related_legend_entry/) | خصائص مدخل الأسطورة المقابل في حالة نوع المخطط من هذه القائمة:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            قراءة فقط [`ILegendEntryProperties`](/slides/python-net/ar/aspose.slides.charts/ilegendentryproperties). |
| [`data_point_levels`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/data_point_levels/) | يعيد حاوية مستويات نقاط البيانات. يُطبق على سلاسل Treeamp و Sunburst.<br/>            فهرسة مستويات نقاط البيانات تبدأ من الصفر. |
| [`index`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/index/) |  |
| [`invert_if_negative`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/invert_if_negative/) | يحدد أن نقطة البيانات يجب أن تعكس ألوانها إذا كانت القيمة سالبًا.<br/>            قراءة/كتابة **bool**. |
| [`cached_value`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/cached_value/) | يحصل على القيمة المخزنة مؤقتًا لنقطة بيانات المخطط.<br/>            قراءة فقط [`ICachedChartValue`](/slides/python-net/ar/aspose.slides.charts/icachedchartvalue). |
| [`cached_x_value`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/cached_x_value/) | يحصل على قيمة X المخزنة مؤقتًا لنقطة بيانات المخطط.<br/>            قراءة فقط [`ICachedChartValue`](/slides/python-net/ar/aspose.slides.charts/icachedchartvalue). |
| [`cached_y_value`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/cached_y_value/) | يحصل على قيمة Y المخزنة مؤقتًا لنقطة بيانات المخطط.<br/>            قراءة فقط [`ICachedChartValue`](/slides/python-net/ar/aspose.slides.charts/icachedchartvalue). |
| [`cached_bubble_size`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/cached_bubble_size/) | يحصل على حجم الفقاعة المخزن مؤقتًا لنقطة بيانات المخطط.<br/>            قراءة فقط [`ICachedChartValue`](/slides/python-net/ar/aspose.slides.charts/icachedchartvalue). |
| [`actual_x`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/actual_x/) | يحدد الموقع الفعلي x (يسار) لعنصر المخطط بالنسبة للزاوية العليا اليسرى للمخطط.<br/>            Call method IChart.ValidateChartLayout() before to get actual values. <br/>            قراءة **float**. |
| [`actual_y`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/actual_y/) | يحدد أعلى العنصر الفعلي للمخطط بالنسبة للزاوية العليا اليسرى للمخطط.<br/>            Call method IChart.ValidateChartLayout() before to get actual values. <br/>            قراءة **float**. |
| [`actual_width`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/actual_width/) | يحدد العرض الفعلي للعنصر في المخطط. Call method IChart.ValidateChartLayout() before to get actual values. <br/>            قراءة **float**. |
| [`actual_height`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/actual_height/) | يحدد الارتفاع الفعلي للعنصر في المخطط. Call method IChart.ValidateChartLayout() before to get actual values. <br/>            قراءة **float**. |

## الطرق

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/remove/#) | يزيل DataPoint من سلسلة المخطط. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/ar/aspose.slides.charts/chartdatapoint/get_automatic_data_point_color/#) | يعيد لونًا تلقائيًا لنقطة البيانات بناءً على فهرس السلسلة، فهرس نقطة البيانات، خاصية ParentSeriesGroup.IsColorVaried، ونمط المخطط.<br/>            يستخدم هذا اللون افتراضيًا إذا كان FillType يساوي NotDefined. |

### انظر أيضًا
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)