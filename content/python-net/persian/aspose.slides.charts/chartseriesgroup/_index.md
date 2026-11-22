---
title: ChartSeriesGroup class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup کلاس

نمایشگر گروهی از سری‌ها.

نوع ChartSeriesGroup اعضای زیر را در اختیار می‌گذارد:

## ویژگی‌ها

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/type/) | نوع این گروه سری را برمی‌گرداند.<br/>            فقط خواندنی [`CombinableSeriesTypesGroup`](/slides/python-net/fa/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | نشان می‌دهد آیا سری‌های این گروه بر روی محور ثانویه رسم می‌شوند.<br/>            فقط خواندنی **bool**. |
| [`series`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/series/) | یک مجموعه از سری‌ها را برمی‌گرداند.<br/>            فقط خواندنی [`IChartSeriesReadonlyCollection`](/slides/python-net/fa/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/up_down_bars/) | دسترسی به نوارهای بالا/پایین نمودار خطی یا سهام را فراهم می‌کند.<br/>            فقط خواندنی [`IUpDownBarsManager`](/slides/python-net/fa/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/gap_width/) | فاصله بین خوشه‌های میله یا ستون را به‌صورت درصدی از عرض میله یا ستون دریافت یا تنظیم می‌کند.<br/>            مقدار باید بین 0 تا 500 باشد.<br/>            خواندنی/نوشتنی **int**. |
| [`gap_depth`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/gap_depth/) | فاصله بین سری‌های داده در یک نمودار سه‌بعدی را به‌صورت درصدی از عرض نشانگر دریافت یا تنظیم می‌کند.<br/>            مقدار باید بین 0 تا 500 باشد.<br/>            خواندنی/نوشتنی **int**. |
| [`first_slice_angle`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | زاویه برش اولین بخش کیک یا دونات را دریافت یا تنظیم می‌کند، <br/>            بر حسب درجه (ساعت‌گرد از بالا، از 0 تا 360 درجه).<br/>            خواندنی/نوشتنی **int**. |
| [`doughnut_hole_size`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | اندازه‌ی سوراخ در نمودار دونات را تعیین می‌کند (می‌تواند بین 0 تا 90 درصد <br/>            از اندازه‌ی ناحیه نمودار باشد).<br/>            خواندنی/نوشتنی **int**. |
| [`overlap`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/overlap/) | تعیین می‌کند که میله‌ها و ستون‌ها در نمودارهای دو-بعدی تا چه حد همپوشانی داشته باشند، به‌صورت درصد (از -100% تا 100%).<br/>             - -100%: بیشینه فاصله (میله‌ها کاملاً جدا هستند).<br/>             - 0%: میله‌ها کنار هم بدون همپوشانی یا فاصله قرار می‌گیرند.<br/>             - 100%: بیشینه همپوشانی (میله‌ها کاملاً بر یکدیگر همپوشانی دارند).<br/>            این ویژگی خواندنی/نوشتنی **int**. |
| [`second_pie_size`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/second_pie_size/) | اندازه‌ی کیک یا میله دوم در نمودار کیک-در-کیك یا میله-در-کیك را به‌صورت درصدی از اندازه‌ی کیک اول تعیین می‌کند (می‌تواند <br/>            بین 5 تا 200 درصد باشد).<br/>            خواندنی/نوشتنی **int**. |
| [`bubble_size_representation`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | نحوه‌ی نمایش مقادیر اندازه حباب‌ها در نمودار حبابی را تعیین می‌کند.<br/>            خواندنی/نوشتنی [`BubbleSizeRepresentationType`](/slides/python-net/fa/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/pie_split_position/) | مقداری که برای تعیین نقاط داده‌ای که در کیک یا میله دوم در نمودار کیک-در-کیك یا میله-در-کیك قرار می‌گیرند، استفاده می‌شود.<br/>            همراه با ویژگی PieSplitBy به کار می‌رود.<br/>            خواندنی/نوشتنی **float**. |
| [`pie_split_by`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/pie_split_by/) | نحوه‌ی تعیین نقاط داده‌ای که در کیک یا میله دوم در نمودار کیک-در-کیك یا میله-در-کیك قرار می‌گیرند را مشخص می‌کند.<br/>            خواندنی/نوشتنی [`PieSplitType`](/slides/python-net/fa/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/is_color_varied/) | تعیین می‌کند که هر نشانگر داده در سری رنگ متفاوتی داشته باشد.<br/>            خواندنی/نوشتنی **bool**. |
| [`has_series_lines`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/has_series_lines/) | اگر نمودار خطوط سری داشته باشد، مقدار true است. برای نمودارهای میله‌ای پشته‌ای و OfPie اعمال می‌شود.<br/>            خواندنی/نوشتنی **bool**. |
| [`hi_low_lines_format`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | قالب HiLowLines را تعیین می‌کند. <br/>            HiLowLines در ترکیب با انواع نمودار HiLowClose، OpenHiLowClose، VolumeHiLowClose و VolumeOpenHiLowClose به‌کار می‌رود. |
| [`bubble_size_scale`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | ضریب مقیاس برای نمودار حبابی را تعیین می‌کند (می‌تواند <br/>            بین 0 تا 300 درصد از اندازه پیش‌فرض باشد).<br/>            خواندنی/نوشتنی **int**. |
| [`pie_split_custom_points`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | اطلاعات تقسیم سفارشی برای نمودار کیک-در-کیك یا میله-در-کیك با تقسیم سفارشی.<br/>            شامل نقاط داده‌ای است که باید در کیک یا میله دوم در نمودار کیک-در-کیك یا <br/>            میله-در-کیك رسم شوند.<br/>            فقط خواندنی [`PieSplitCustomPointCollection`](/slides/python-net/fa/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/chart/) | نمودار والد را برمی‌گرداند.<br/>            فقط خواندنی [`IChart`](/slides/python-net/fa/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/presentation/) |  |

عنصری را که در شاخص مشخص شده قرار دارد، دریافت می‌کند.

## Indexer

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |

### توضیحات

1) خلاصه و توضیحات مربوط به کلاس ChartSeriesGroupCollection و enum CombinableSeriesTypesGroup را ببینید.
            2) گروهی از سری‌ها شامل برخی ویژگی‌های سری است که برای هر سری در گروه مشترک است ("ویژگی‌های گروه سری").
            «ویژگی‌های گروه سری» در کلاس ChartSeriesGroup خواندنی/نوشتنی است.
            هر یک از «ویژگی‌های گروه سری» می‌تواند یک پروژکشن فقط‌خواندنی در کلاس ChartSeries داشته باشد.

### موارد مرتبط
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)