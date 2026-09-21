---
title: ChartSeriesGroup class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.charts/chartseriesgroup/
---
## کلاس ChartSeriesGroup

نمایانگر گروهی از سری‌ها است.

نوع ChartSeriesGroup اعضای زیر را نمایش می‌دهد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`type`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/type/) | نوعی از این گروه سری را برمی‌گرداند.<br/>            فقط-خواندنی [`CombinableSeriesTypesGroup`](/slides/python-net/fa/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | مشخص می‌کند آیا سری‌های این گروه بر روی محور ثانویه رسم می‌شوند.<br/>            فقط-خواندنی **bool**. |
| [`series`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/series/) | یک مجموعه از سری‌ها را برمی‌گرداند.<br/>            فقط-خواندنی [`IChartSeriesReadonlyCollection`](/slides/python-net/fa/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/up_down_bars/) | دسترسی به نوارهای بالا/پایین نمودار خط یا سهام را فراهم می‌کند.<br/>            فقط-خواندنی [`IUpDownBarsManager`](/slides/python-net/fa/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/gap_width/) | فاصله بین خوشه‌های میله یا ستون را به عنوان درصدی از عرض میله یا ستون مشخص می‌کند.<br/>            قابل‌خواندن/قابل‌نوشتن **int**. |
| [`gap_depth`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/gap_depth/) | فاصله بین سری‌های داده در یک نمودار 3 بعدی را به عنوان درصدی از عرض مارکر برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/قابل‌نوشتن **int**. |
| [`first_slice_angle`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | زاویهٔ اولین برش نمودار کیک یا دونات را دریافت یا تنظیم می‌کند، <br/>            به درجه (در جهت ساعتگرد از بالا، از ۰ تا ۳۶۰ درجه).<br/>            قابل‌خواندن/قابل‌نوشتن **int**. |
| [`doughnut_hole_size`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | اندازهٔ حفره در نمودار دونات را تعیین می‌کند (می‌تواند بین ۰ تا ۹۰ درصد از اندازهٔ ناحیهٔ ترسیم باشد).<br/>            قابل‌خواندن/قابل‌نوشتن **int**. |
| [`overlap`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/overlap/) | نسبت همپوشانی میله‌ها و ستون‌ها در نمودارهای دو-بعدی را به صورت درصد (از -۱۰۰٪ تا ۱۰۰٪) مشخص می‌کند.<br/>             -100٪: بیشترین فاصله (میله‌ها کاملاً جدا هستند).<br/>             0٪: میله‌ها بدون همپوشانی یا فاصله کنار هم قرار می‌گیرند.<br/>             100٪: بیشترین همپوشانی (میله‌ها کاملاً یکدیگر را پوشش می‌دهند).<br/>             این ویژگی قابل‌خواندن/قابل‌نوشتن **int** است. |
| [`second_pie_size`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/second_pie_size/) | اندازهٔ کیک یا میلهٔ دوم در نمودار کیک-از-کیک یا میله-از-کیک را به‌عنوان درصدی از اندازهٔ کیک اول تعیین می‌کند (می‌تواند بین ۵ تا ۲۰۰ درصد باشد).<br/>            قابل‌خواندن/قابل‌نوشتن **int**. |
| [`bubble_size_representation`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | نحوهٔ نمایش مقادیر اندازهٔ حباب‌ها در نمودار حبابی را مشخص می‌کند.<br/>            قابل‌خواندن/قابل‌نوشتن [`BubbleSizeRepresentationType`](/slides/python-net/fa/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/pie_split_position/) | مقداری را تعیین می‌کند که برای مشخص کردن اینکه کدام نقاط داده در کیک یا میله دوم در نمودار کیک-از-کیک یا میله-از-کیک قرار دارند استفاده می‌شود.<br/>            به همراه ویژگی PieSplitBy استفاده می‌شود.<br/>            قابل‌خواندن/قابل‌نوشتن **float**. |
| [`pie_split_by`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/pie_split_by/) | نحوهٔ تعیین اینکه کدام نقاط داده در کیک یا میله دوم در نمودار کیک-از-کیک یا میله-از-کیک قرار دارند را مشخص می‌کند.<br/>            قابل‌خواندن/قابل‌نوشتن [`PieSplitType`](/slides/python-net/fa/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/is_color_varied/) | مشخص می‌کند که هر نشانگر داده در سری رنگ متفاوتی دارد.<br/>            قابل‌خواندن/قابل‌نوشتن **bool**. |
| [`has_series_lines`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/has_series_lines/) | در صورتی که نمودار خطوط سری داشته باشد، مقدار True است. برای نمودارهای میلهٔ پشته‌ای و OfPie اعمال می‌شود.<br/>            قابل‌خواندن/قابل‌نوشتن **bool**. |
| [`hi_low_lines_format`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | قالب HiLowLines را مشخص می‌کند. <br/>            HiLowLines با انواع نمودار HiLowClose، OpenHiLowClose، VolumeHiLowClose و VolumeOpenHiLowClose اعمال می‌شود. |
| [`bubble_size_scale`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | فاکتور مقیاس برای نمودار حبابی را تعیین می‌کند (می‌تواند بین ۰ تا ۳۰۰ درصد از اندازهٔ پیش‌فرض باشد).<br/>            قابل‌خواندن/قابل‌نوشتن **int**. |
| [`pie_split_custom_points`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | اطلاعات تقسیم سفارشی برای نمودار کیک-از-کیک یا میله-از-کیک با تقسیم سفارشی.<br/>            شامل نقاط داده‌ای است که باید در کیک یا میله دوم در نمودار کیک-از-کیک یا میله-از-کیک رسم شوند.<br/>            فقط-خواندنی [`PieSplitCustomPointCollection`](/slides/python-net/fa/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/chart/) | نمودار والد را برمی‌گرداند.<br/>            فقط-خواندنی [`IChart`](/slides/python-net/fa/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/presentation/) |  |

عنصر را در اندیس مشخص‌شده دریافت می‌کند.

## ایندکسر

| نام | توضیح |
| :- | :- |
| [`[index]`](/slides/python-net/fa/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |

### توضیحات

1) خلاصه و توضیحات مربوط به کلاس ChartSeriesGroupCollection و enum CombinableSeriesTypesGroup را ببینید.  
2) گروه سری‌ها شامل برخی از ویژگی‌های سری است که برای هر سری در گروه مشترک است ("ویژگی‌های گروه سری").  
   "ویژگی‌های گروه سری" در کلاس ChartSeriesGroup فقط-قابل‌خواندن/قابل‌نوشتن است.  
   هر یک از "ویژگی‌های گروه سری" می‌توانند یک تصویر فقط-خواندنی در کلاس ChartSeries داشته باشند.

### مراجع
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)