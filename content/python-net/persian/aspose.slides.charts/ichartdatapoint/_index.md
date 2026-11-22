---
title: IChartDataPoint class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint کلاس

نقطه داده‌ای سری را نمایش می‌دهد.

نوع IChartDataPoint اعضای زیر را در دسترس قرار می‌دهد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`x_value`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/x_value/) | مقدار x یک نقطه داده نمودار را دریافت می‌کند.<br/>            فقط خواندنی [`IStringOrDoubleChartValue`](/slides/python-net/fa/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/y_value/) | مقدار y یک نقطه داده نمودار را دریافت می‌کند.<br/>            فقط خواندنی [`IDoubleChartValue`](/slides/python-net/fa/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/bubble_size/) | اندازه حباب یک نقطه داده نمودار را دریافت می‌کند.<br/>            فقط خواندنی [`IDoubleChartValue`](/slides/python-net/fa/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/value/) | مقدار یک نقطه داده نمودار را دریافت می‌کند.<br/>            فقط خواندنی [`IDoubleChartValue`](/slides/python-net/fa/aspose.slides.charts/idoublechartvalue). |
| [`cached_x_value`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/cached_x_value/) | مقدار X ذخیره‌شده یک نقطه داده نمودار را دریافت می‌کند.<br/>            فقط خواندنی [`ICachedChartValue`](/slides/python-net/fa/aspose.slides.charts/icachedchartvalue). |
| [`cached_y_value`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/cached_y_value/) | مقدار Y ذخیره‌شده یک نقطه داده نمودار را دریافت می‌کند.<br/>            فقط خواندنی [`ICachedChartValue`](/slides/python-net/fa/aspose.slides.charts/icachedchartvalue). |
| [`cached_value`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/cached_value/) | مقدار ذخیره‌شده یک نقطه داده نمودار را دریافت می‌کند.<br/>            فقط خواندنی [`ICachedChartValue`](/slides/python-net/fa/aspose.slides.charts/icachedchartvalue). |
| [`cached_bubble_size`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/cached_bubble_size/) | اندازه حباب ذخیره‌شده یک نقطه داده نمودار را دریافت می‌کند.<br/>            فقط خواندنی [`ICachedChartValue`](/slides/python-net/fa/aspose.slides.charts/icachedchartvalue). |
| [`size_value`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/size_value/) | مقدار اندازه یک نقطه داده نمودار را دریافت می‌کند.<br/>            در نمودارهای Treemap و Sunburst استفاده می‌شود. <br/>            فقط خواندنی [`IDoubleChartValue`](/slides/python-net/fa/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/color_value/) | مقدار رنگ یک نقطه داده نمودار را دریافت می‌کند.<br/>            در نمودارهای نقشه استفاده می‌شود. <br/>            فقط خواندنی [`IDoubleChartValue`](/slides/python-net/fa/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | مقادیر نوارهای خطای سری را در صورت نوع مقدار Custom نمایش می‌دهد.<br/>            فقط خواندنی [`IErrorBarsCustomValues`](/slides/python-net/fa/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/label/) | برچسب یک نقطه داده نمودار را نمایش می‌دهد.<br/>            فقط خواندنی [`IDataLabel`](/slides/python-net/fa/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | مشخص می‌کند که حباب‌ها اثر 3-بعدی دارند.<br/>            قابل خواندن و نوشتن **bool**. |
| [`explosion`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/explosion/) | مقدارى که نقطه داده از مرکز دایره باید جابجا شود را مشخص می‌کند.<br/>            قابل خواندن و نوشتن **int**. |
| [`format`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/format/) | خصوصیات قالب‌بندی را نمایش می‌دهد.<br/>            قابل خواندن و نوشتن [`IFormat`](/slides/python-net/fa/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/marker/) | یک نشانگر داده را مشخص می‌کند.<br/>            فقط خواندنی [`IMarker`](/slides/python-net/fa/aspose.slides.charts/imarker). |
| [`related_legend_entry`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | خصوصیات ورودی افسانه مربوطه در صورت نوع نمودار از لیست زیر: <br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            فقط خواندنی [`ILegendEntryProperties`](/slides/python-net/fa/aspose.slides.charts/ilegendentryproperties). |
| [`set_as_total`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/set_as_total/) | نقطه داده را به عنوان مجموع تنظیم می‌کند. فقط برای نوع سری Waterfall اعمال می‌شود. |
| [`invert_if_negative`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | مشخص می‌کند که نقطه داده در صورت مقدار منفی رنگ‌های خود را معکوس کند.<br/>            قابل خواندن و نوشتن **bool**. |
| [`data_point_levels`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/data_point_levels/) | محتویات سطوح نقطه داده را برمی‌گرداند. برای سری‌های Treeamp و Sunburst اعمال می‌شود.<br/>            اندیس‌بندی سطوح نقطه داده از صفر شروع می‌شود. |
| [`index`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/index/) | تعیین می‌کند که این نقطه داده به کدام مجموعه فرزند والد اعمال می‌شود.<br/>            قابل خواندن **int**. |
| [`actual_x`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [`actual_y`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [`actual_width`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [`actual_height`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## متدها

| متد | توضیح |
| :- | :- |
| [`remove(self)`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/remove/#) | DataPoint را از سری نمودار حذف می‌کند. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/get_automatic_data_point_color/#) | یک رنگ خودکار برای نقطه داده بر اساس فهرست سری، فهرست نقطه داده، ویژگی ParentSeriesGroup.IsColorVaried و سبک نمودار برمی‌گرداند. <br/>            این رنگ به‌طور پیش‌فرض اگر FillType برابر NotDefined باشد استفاده می‌شود. |

### سایر موارد
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)