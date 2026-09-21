---
title: IChartDataPoint class
second_title: مستندات API Aspose.Slides برای پایتون از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint کلاس

نقطه داده سری را نشان می‌دهد.

نوع IChartDataPoint اعضای زیر را ارائه می‌دهد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`x_value`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/x_value/) | مقدار x نقطه داده نمودار را برمی‌گرداند.<br/>            فقط‌خواندنی [`IStringOrDoubleChartValue`](/slides/python-net/fa/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/y_value/) | مقدار y نقطه داده نمودار را برمی‌گرداند.<br/>            فقط‌خواندنی [`IDoubleChartValue`](/slides/python-net/fa/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/bubble_size/) | اندازه حباب نقطه داده نمودار را برمی‌گرداند.<br/>            فقط‌خواندنی [`IDoubleChartValue`](/slides/python-net/fa/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/value/) | مقدار نقطه داده نمودار را برمی‌گرداند.<br/>            فقط‌خواندنی [`IDoubleChartValue`](/slides/python-net/fa/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/size_value/) | مقدار ابعاد نقطه داده نمودار را برمی‌گرداند.<br/>            در نمودارهای Treemap و Sunburst استفاده می‌شود. <br/>            فقط‌خواندنی [`IDoubleChartValue`](/slides/python-net/fa/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/color_value/) | مقدار رنگ نقطه داده نمودار را برمی‌گرداند.<br/>            در نمودارهای Map استفاده می‌شود. <br/>            فقط‌خواندنی [`IDoubleChartValue`](/slides/python-net/fa/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | مقدار نوارهای خطای سری را در حالت نوع مقدار Custom نمایش می‌دهد.<br/>            فقط‌خواندنی [`IErrorBarsCustomValues`](/slides/python-net/fa/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/label/) | نمایش برچسب نقطه داده نمودار.<br/>            فقط‌خواندنی [`IDataLabel`](/slides/python-net/fa/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | مشخص می‌کند که حباب‌ها دارای اثر 3-بعدی هستند.<br/>            خواندنی/نوشتنی **bool**. |
| [`explosion`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/explosion/) | مقداری که نقطه داده از مرکز دایره کیک جابجا شود را مشخص می‌کند.<br/>            خواندنی/نوشتنی **int**. |
| [`format`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/format/) | ویژگی‌های قالب‌بندی را نمایش می‌دهد.<br/>            خواندنی/نوشتنی [`IFormat`](/slides/python-net/fa/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/marker/) | یک نشانگر داده را مشخص می‌کند.<br/>            فقط‌خواندنی [`IMarker`](/slides/python-net/fa/aspose.slides.charts/imarker). |
| [`related_legend_entry`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | ویژگی‌های ورودی افسانهٔ مربوطه در صورتی که نوع نمودار از این فهرست باشد:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            فقط‌خواندنی [`ILegendEntryProperties`](/slides/python-net/fa/aspose.slides.charts/ilegendentryproperties). |
| [`set_as_total`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/set_as_total/) | نقطه داده را به عنوان مجموع تنظیم می‌کند. فقط برای نوع سری Waterfall اعمال می‌شود. |
| [`invert_if_negative`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | مشخص می‌کند که اگر مقدار منفی باشد، رنگ‌های نقطه داده معکوس می‌شود.<br/>            خواندنی/نوشتنی **bool**. |
| [`data_point_levels`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/data_point_levels/) | مخزنی از سطوح نقطه داده را برمی‌گرداند. برای سری‌های Treeamp و Sunburst اعمال می‌شود.<br/>            ایندکس‌گذاری سطوح نقطه داده از صفر شروع می‌شود. |
| [`index`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/index/) | مشخص می‌کند که این نقطه داده به کدام مجموعه فرزندان والد اعمال می‌شود.<br/>            خواندنی **int**. |
| [`actual_x`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [`actual_y`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [`actual_width`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [`actual_height`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## متدها

| متد | توضیح |
| :- | :- |
| [`remove(self)`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/remove/#) | DataPoint را از سری نمودار حذف می‌کند. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/get_automatic_data_point_color/#) | یک رنگ خودکار برای نقطه داده بر اساس ایندکس سری، ایندکس نقطه داده، خاصیت ParentSeriesGroup.IsColorVaried و سبک نمودار برمی‌گرداند.<br/>            این رنگ به طور پیش‌فرض استفاده می‌شود اگر FillType برابر NotDefined باشد. |

### موارد مرتبط
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)