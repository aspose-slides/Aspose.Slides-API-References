---
title: ChartDataPoint class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint کلاس

نمایانگر نقطه داده سری است.

نوع ChartDataPoint اعضای زیر را ارائه می‌دهد:

## خواص

| ویژگی | شرح |
| :- | :- |
| [`x_value`](/slides/python-net/fa/aspose.slides.charts/chartdatapoint/x_value/) | XValue.<br/>            فقط-خواندنی [`IStringOrDoubleChartValue`](/slides/python-net/fa/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/fa/aspose.slides.charts/chartdatapoint/y_value/) | YValue.<br/>            فقط-خواندنی [`IDoubleChartValue`](/slides/python-net/fa/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/fa/aspose.slides.charts/chartdatapoint/bubble_size/) | BubbleSize.<br/>            فقط-خواندنی [`IDoubleChartValue`](/slides/python-net/fa/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/fa/aspose.slides.charts/chartdatapoint/value/) | Value.<br/>            فقط-خواندنی [`IDoubleChartValue`](/slides/python-net/fa/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/fa/aspose.slides.charts/chartdatapoint/size_value/) | مقدار اندازه نقطه داده نمودار را بر می‌گرداند.<br/>            برای نمودارهای Treemap و Sunburst استفاده می‌شود. <br/>            فقط-خواندنی [`IDoubleChartValue`](/slides/python-net/fa/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/fa/aspose.slides.charts/chartdatapoint/color_value/) | مقدار رنگ نقطه داده نمودار را بر می‌گرداند.<br/>            برای نمودارهای Map استفاده می‌شود. <br/>            فقط-خواندنی [`IDoubleChartValue`](/slides/python-net/fa/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/fa/aspose.slides.charts/chartdatapoint/error_bars_custom_values/) | مقادیر نوارهای خطا سری را در صورت نوع مقدار سفارشی نشان می‌دهد.<br/>            فقط-خواندنی [`IErrorBarsCustomValues`](/slides/python-net/fa/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/fa/aspose.slides.charts/chartdatapoint/label/) | Label.<br/>            فقط-خواندنی [`IDataLabel`](/slides/python-net/fa/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/fa/aspose.slides.charts/chartdatapoint/is_bubble_3d/) | مشخص می‌کند که حباب‌ها اثر سه‌بعدی دارند.<br/>            خواندنی/نوشتنی **bool**. |
| [`explosion`](/slides/python-net/fa/aspose.slides.charts/chartdatapoint/explosion/) | مقدار جابجایی نقطه داده از مرکز دایره کیک را مشخص می‌کند.<br/>            خواندنی/نوشتنی **int**. |
| [`format`](/slides/python-net/fa/aspose.slides.charts/chartdatapoint/format/) | ویژگی‌های قالب‌بندی را نشان می‌دهد.<br/>            خواندنی/نوشتنی [`IFormat`](/slides/python-net/fa/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/fa/aspose.slides.charts/chartdatapoint/marker/) | یک نشانگر داده را مشخص می‌کند.<br/>            فقط-خواندنی [`IMarker`](/slides/python-net/fa/aspose.slides.charts/imarker). |
| [`set_as_total`](/slides/python-net/fa/aspose.slides.charts/chartdatapoint/set_as_total/) | نقطه داده را به‌عنوان مجموع تنظیم می‌کند. فقط برای نوع سری Waterfall کاربرد دارد. |
| [`related_legend_entry`](/slides/python-net/fa/aspose.slides.charts/chartdatapoint/related_legend_entry/) | ویژگی‌های ورودی افسانه متناظر در‌صورت نوع نمودار از فهرست زیر:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            فقط-خواندنی [`ILegendEntryProperties`](/slides/python-net/fa/aspose.slides.charts/ilegendentryproperties). |
| [`data_point_levels`](/slides/python-net/fa/aspose.slides.charts/chartdatapoint/data_point_levels/) | محفظه سطوح نقطه داده را بر می‌گرداند. برای سری‌های Treeamp و Sunburst کاربرد دارد.<br/>            ایندکس سطوح نقطه داده از صفر شروع می‌شود. |
| [`index`](/slides/python-net/fa/aspose.slides.charts/chartdatapoint/index/) |  |
| [`invert_if_negative`](/slides/python-net/fa/aspose.slides.charts/chartdatapoint/invert_if_negative/) | مشخص می‌کند که نقطه داده در صورت مقدار منفی رنگ‌های خود را معکوس کند.<br/>            خواندنی/نوشتنی **bool**. |
| [`actual_x`](/slides/python-net/fa/aspose.slides.charts/chartdatapoint/actual_x/) | موقعیت واقعی x (چپ) عنصر نمودار نسبت به گوشه بالای چپ نمودار را مشخص می‌کند.<br/>            قبل از دریافت مقادیر واقعی متد IChart.ValidateChartLayout() را فراخوانی کنید. <br/>            خواندنی **float**. |
| [`actual_y`](/slides/python-net/fa/aspose.slides.charts/chartdatapoint/actual_y/) | موقعیت واقعی بالای عنصر نمودار نسبت به گوشه بالای چپ نمودار را مشخص می‌کند.<br/>            قبل از دریافت مقادیر واقعی متد IChart.ValidateChartLayout() را فراخوانی کنید. <br/>            خواندنی **float**. |
| [`actual_width`](/slides/python-net/fa/aspose.slides.charts/chartdatapoint/actual_width/) | عرض واقعی عنصر نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی متد IChart.ValidateChartLayout() را فراخوانی کنید. <br/>            خواندنی **float**. |
| [`actual_height`](/slides/python-net/fa/aspose.slides.charts/chartdatapoint/actual_height/) | ارتفاع واقعی عنصر نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی متد IChart.ValidateChartLayout() را فراخوانی کنید. <br/>            خواندنی **float**. |

## متدها

| متد | شرح |
| :- | :- |
| [`remove(self)`](/slides/python-net/fa/aspose.slides.charts/chartdatapoint/remove/#) | نقطه داده را از سری نمودار حذف می‌کند. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/fa/aspose.slides.charts/chartdatapoint/get_automatic_data_point_color/#) | یک رنگ خودکار برای نقطه داده بر اساس ایندکس سری، ایندکس نقطه داده، ویژگی ParentSeriesGroup.IsColorVaried و سبک نمودار بر می‌گرداند.<br/>            این رنگ به‌طور پیش‌فرض زمانی استفاده می‌شود که FillType برابر NotDefined باشد. |

### مراجع مرتبط
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)