---
title: IChartSeriesGroup class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup کلاس

نمایشگر گروهی از سری‌ها.

IChartSeriesGroup نوع اعضای زیر را نشان می‌دهد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`type`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/type/) | یک نوع از این گروه سری را برمی‌گرداند.<br/>فقط‌خواندنی [`CombinableSeriesTypesGroup`](/slides/python-net/fa/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | نشان می‌دهد آیا سری‌های این گروه روی محور ثانویه رسم می‌شوند.<br/>فقط‌خواندنی **bool**. |
| [`series`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/series/) | یک مجموعه فقط‌خواندنی از سری‌های نمودار را برمی‌گرداند.<br/>فقط‌خواندنی [`IChartSeriesReadonlyCollection`](/slides/python-net/fa/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | دسترسی به نوارهای بالا/پایین نمودار خط یا سهام را فراهم می‌کند.<br/>فقط‌خواندنی [`IUpDownBarsManager`](/slides/python-net/fa/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/gap_width/) | فضای بین خوشه‌های میله یا ستون را به‌صورت درصدی از عرض میله یا ستون دریافت یا تنظیم می‌کند.<br/>مقدار باید بین ۰ و ۵۰۰ باشد.<br/>خواندنی/نوشتنی **int**. |
| [`gap_depth`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/gap_depth/) | فاصله بین سری‌های داده در یک نمودار ۳-بعدی را به‌صورت درصدی از عرض علامت دریافت یا تنظیم می‌کند.<br/>مقدار باید بین ۰ و ۵۰۰ باشد.<br/>خواندنی/نوشتنی **int**. |
| [`first_slice_angle`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | زاویهٔ اولین برش نمودار پای یا دونات را دریافت یا تنظیم می‌کند،<br/>به‌درجه (ساعتگرد از بالا، از ۰ تا ۳۶۰ درجه).<br/>خواندنی/نوشتنی **int**. |
| [`is_color_varied`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | مشخص می‌کند که هر نشانگر داده در سری رنگ متفاوتی دارد.<br/>خواندنی/نوشتنی **bool**. |
| [`has_series_lines`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | درست اگر نمودار خطوط سری داشته باشد. برای نمودارهای میلهٔ پشته‌ای و OfPie اعمال می‌شود.<br/>خواندنی/نوشتنی **bool**. |
| [`overlap`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/overlap/) | مشخص می‌کند که میله‌ها و ستون‌ها تا چه حد در نمودارهای دو-بعدی هم‌پوشانی داشته باشند، به‌صورت درصد (از -۱۰۰٪ تا ۱۰۰٪).<br/>- -۱۰۰٪: حداکثر فاصله (میله‌ها کاملاً جدا هستند).<br/>- ۰٪: میله‌ها کنار هم بدون هم‌پوشانی یا فاصله قرار می‌گیرند.<br/>- ۱۰۰٪: حداکثر هم‌پوشانی (میله‌ها کاملاً روی هم قرار می‌گیرند).<br/>این ویژگی خواندنی/نوشتنی **int**. |
| [`second_pie_size`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | اندازهٔ پای دوم یا میلهٔ نمودار پای-از-پای یا میله-از-پای را به‌صورت درصدی از اندازهٔ پای اول مشخص می‌کند (می‌تواند بین ۵ تا ۲۰۰ درصد باشد).<br/>خواندنی/نوشتنی **int**. |
| [`pie_split_position`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | مقداری را مشخص می‌کند که برای تعیین نقاط داده‌ای که در پای یا میلهٔ دوم در یک نمودار پای-از-پای یا میله-از-پای هستند، استفاده می‌شود.<br/>همزمان با ویژگی PieSplitBy استفاده می‌شود.<br/>خواندنی/نوشتنی **float**. |
| [`pie_split_by`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | نحوه تعیین نقاط داده‌ای که در پای یا میلهٔ دوم در یک نمودار پای-از-پای یا میله-از-پای هستند را مشخص می‌کند.<br/>خواندنی/نوشتنی [`PieSplitType`](/slides/python-net/fa/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | اطلاعات تقسیم سفارشی برای یک نمودار پای-از-پای یا میله-از-پای با تقسیم سفارشی.<br/>شامل نقاط داده‌ای که باید در پای یا میلهٔ دوم در یک نمودار پای-از-پای یا میله-از-پای رسم شوند.<br/>فقط‌خواندنی [`IPieSplitCustomPointCollection`](/slides/python-net/fa/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`doughnut_hole_size`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | اندازهٔ سوراخ در یک نمودار دونات را مشخص می‌کند (می‌تواند بین ۱۰ تا ۹۰ درصد از اندازهٔ ناحیهٔ نمودار باشد).<br/>خواندنی/نوشتنی **int**. |
| [`bubble_size_scale`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | عامل مقیاس برای نمودار حبابی را مشخص می‌کند (می‌تواند بین ۰ تا ۳۰۰ درصد از اندازهٔ پیش‌فرض باشد).<br/>خواندنی/نوشتنی **int**. |
| [`hi_low_lines_format`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | قالب HiLowLines را مشخص می‌کند.<br/>HiLowLines در ترکیب با انواع نمودار HiLowClose، OpenHiLowClose، VolumeHiLowClose و VolumeOpenHiLowClose اعمال می‌شود. |
| [`bubble_size_representation`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | نحوهٔ نمایش مقادیر اندازهٔ حباب در نمودار حبابی را مشخص می‌کند.<br/>خواندنی/نوشتنی [`BubbleSizeRepresentationType`](/slides/python-net/fa/aspose.slides.charts/bubblesizerepresentationtype). |
| [`chart`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

عنصر موجود در ایندکس مشخص‌شده را دریافت می‌کند.

## ایندکس

| نام | توضیح |
| :- | :- |
| [`[index]`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |

### ملاحظات

1) برای خلاصه و ملاحظات کلاس ChartSeriesGroupCollection و enum CombinableSeriesTypesGroup مراجعه کنید.
2) گروهی از سری‌ها شامل برخی ویژگی‌های سری است که برای هر سری در گروه مشترک است ("series group properties").
"Series group properties" در کلاس ChartSeriesGroup خواندنی/نوشتنی است.
هر یک از "series group properties" می‌تواند یک پروجکشن فقط-خواندنی در کلاس ChartSeries داشته باشد.

### مراجع
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)