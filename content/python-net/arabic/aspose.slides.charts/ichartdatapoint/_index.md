---
title: IChartDataPoint class
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/ichartdatapoint/
---
## الفئة IChartDataPoint

يمثل نقطة بيانات سلسلة.

نوع IChartDataPoint يكشف عن الأعضاء التالية:

## الخصائص

| خاصية | الوصف |
| :- | :- |
| [`x_value`](/slides/python-net/ar/aspose.slides.charts/ichartdatapoint/x_value/) | يحصل على قيمة x لنقطة بيانات المخطط.<br/>            للقراءة فقط [`IStringOrDoubleChartValue`](/slides/python-net/ar/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/ar/aspose.slides.charts/ichartdatapoint/y_value/) | يحصل على قيمة y لنقطة بيانات المخطط.<br/>            للقراءة فقط [`IDoubleChartValue`](/slides/python-net/ar/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/ar/aspose.slides.charts/ichartdatapoint/bubble_size/) | يحصل على حجم الفقاعة لنقطة بيانات المخطط.<br/>            للقراءة فقط [`IDoubleChartValue`](/slides/python-net/ar/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/ar/aspose.slides.charts/ichartdatapoint/value/) | يحصل على قيمة نقطة بيانات المخطط.<br/>            للقراءة فقط [`IDoubleChartValue`](/slides/python-net/ar/aspose.slides.charts/idoublechartvalue). |
| [`cached_x_value`](/slides/python-net/ar/aspose.slides.charts/ichartdatapoint/cached_x_value/) | يحصل على القيمة المخزنة X لنقطة بيانات المخطط.<br/>            للقراءة فقط [`ICachedChartValue`](/slides/python-net/ar/aspose.slides.charts/icachedchartvalue). |
| [`cached_y_value`](/slides/python-net/ar/aspose.slides.charts/ichartdatapoint/cached_y_value/) | يحصل على القيمة المخزنة Y لنقطة بيانات المخطط.<br/>            للقراءة فقط [`ICachedChartValue`](/slides/python-net/ar/aspose.slides.charts/icachedchartvalue). |
| [`cached_value`](/slides/python-net/ar/aspose.slides.charts/ichartdatapoint/cached_value/) | يحصل على القيمة المخزنة لنقطة بيانات المخطط.<br/>            للقراءة فقط [`ICachedChartValue`](/slides/python-net/ar/aspose.slides.charts/icachedchartvalue). |
| [`cached_bubble_size`](/slides/python-net/ar/aspose.slides.charts/ichartdatapoint/cached_bubble_size/) | يحصل على حجم الفقاعة المخزن لنقطة بيانات المخطط.<br/>            للقراءة فقط [`ICachedChartValue`](/slides/python-net/ar/aspose.slides.charts/icachedchartvalue). |
| [`size_value`](/slides/python-net/ar/aspose.slides.charts/ichartdatapoint/size_value/) | يحصل على قيمة الحجم لنقطة بيانات المخطط.<br/>            يستخدم مع مخططات Treemap و Sunburst.<br/>            للقراءة فقط [`IDoubleChartValue`](/slides/python-net/ar/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/ar/aspose.slides.charts/ichartdatapoint/color_value/) | يحصل على قيمة اللون لنقطة بيانات المخطط.<br/>            يستخدم مع مخططات Map.<br/>            للقراءة فقط [`IDoubleChartValue`](/slides/python-net/ar/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/ar/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | يمثل قيم أشرطة الخطأ للسلسلة في حالة نوع القيمة المخصص.<br/>            للقراءة فقط [`IErrorBarsCustomValues`](/slides/python-net/ar/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/ar/aspose.slides.charts/ichartdatapoint/label/) | يمثل تسمية نقطة بيانات المخطط.<br/>            للقراءة فقط [`IDataLabel`](/slides/python-net/ar/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/ar/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | يحدد أن الفقاعات لديها تأثير ثلاثي الأبعاد مطبق عليها.<br/>            قراءة/كتابة **bool**. |
| [`explosion`](/slides/python-net/ar/aspose.slides.charts/ichartdatapoint/explosion/) | يحدد مقدار تحريك نقطة البيانات من مركز الدائرة.<br/>            قراءة/كتابة **int**. |
| [`format`](/slides/python-net/ar/aspose.slides.charts/ichartdatapoint/format/) | يمثل خصائص التنسيق.<br/>            قراءة/كتابة [`IFormat`](/slides/python-net/ar/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/ar/aspose.slides.charts/ichartdatapoint/marker/) | يحدد علامة البيانات.<br/>            للقراءة فقط [`IMarker`](/slides/python-net/ar/aspose.slides.charts/imarker). |
| [`related_legend_entry`](/slides/python-net/ar/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | خصائص إدخال الأسطورة المقابل في حالة نوع المخطط من هذه القائمة:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            للقراءة فقط [`ILegendEntryProperties`](/slides/python-net/ar/aspose.slides.charts/ilegendentryproperties). |
| [`set_as_total`](/slides/python-net/ar/aspose.slides.charts/ichartdatapoint/set_as_total/) | يحدد نقطة البيانات كإجمالي. يُطبّق فقط على سلسلة Waterfall. |
| [`invert_if_negative`](/slides/python-net/ar/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | يحدد أن نقطة البيانات يجب أن تعكس ألوانها إذا كانت القيمة سلبية.<br/>            قراءة/كتابة **bool**. |
| [`data_point_levels`](/slides/python-net/ar/aspose.slides.charts/ichartdatapoint/data_point_levels/) | يرجع حاوية مستويات نقطة البيانات. يُطبق على سلسلتي Treeamp و Sunburst.<br/>            فهرسة مستويات نقطة البيانات يبدأ من الصفر. |
| [`index`](/slides/python-net/ar/aspose.slides.charts/ichartdatapoint/index/) | يحدد أي مجموعة من أطفال العنصر الأب تنطبق عليها نقطة البيانات هذه.<br/>            قراءة **int**. |
| [`actual_x`](/slides/python-net/ar/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [`actual_y`](/slides/python-net/ar/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [`actual_width`](/slides/python-net/ar/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [`actual_height`](/slides/python-net/ar/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## الطرق

| طريقة | الوصف |
| :- | :- |
| [`remove(self)`](/slides/python-net/ar/aspose.slides.charts/ichartdatapoint/remove/#) | يزيل DataPoint من سلسلة المخطط. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/ar/aspose.slides.charts/ichartdatapoint/get_automatic_data_point_color/#) | يرجع لونًا تلقائيًا لنقطة البيانات بناءً على فهرس السلسلة، فهرس نقطة البيانات، الخاصية ParentSeriesGroup.IsColorVaried ونمط المخطط.<br/>            يستخدم هذا اللون بشكل افتراضي إذا كان FillType يساوي NotDefined. |

### راجع أيضًا
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)