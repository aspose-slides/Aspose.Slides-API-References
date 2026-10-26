---
title: IChartSeriesGroup class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup کلاس

نمایانگر گروهی از سلسله‌ها است.

نوع IChartSeriesGroup اعضای زیر را ارائه می‌دهد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`type`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/type/) | نوع این گروه سلسله را برمی‌گرداند.<br/>            فقط-خواندنی [`CombinableSeriesTypesGroup`](/slides/python-net/fa/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | نشان می‌دهد که آیا سلسله‌های این گروه بر روی محور ثانویه رسم می‌شوند.<br/>            فقط-خواندنی **bool**. |
| [`series`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/series/) | یک مجموعه فقط-خواندنی از سلسله‌های نمودار را برمی‌گرداند.<br/>            فقط-خواندنی [`IChartSeriesReadonlyCollection`](/slides/python-net/fa/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | دسترسی به نوارهای بالا/پایین نمودار خطی یا سهام را فراهم می‌کند.<br/>            فقط-خواندنی [`IUpDownBarsManager`](/slides/python-net/fa/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/gap_width/) | فضای بین خوشه‌های نوار یا ستون را به‌عنوان درصدی از عرض نوار یا ستون مشخص می‌کند.<br/>            قابل‌خواندن/قابل‌نوشتن **int**. |
| [`gap_depth`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/gap_depth/) | فاصله را که به‌عنوان درصدی از عرض مارکر بین سلسله‌های داده در نمودار 3D است، برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/قابل‌نوشتن **int**. |
| [`first_slice_angle`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | زاویه اولین برش نمودار پای یا دونات را دریافت یا تنظیم می‌کند، <br/>            بر حسب درجه (ساعتگرد از بالا، از 0 تا 360 درجه).<br/>            قابل‌خواندن/قابل‌نوشتن **int**. |
| [`is_color_varied`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | مشخص می‌کند که هر علامت داده در سلسله رنگ متفاوتی داشته باشد.<br/>            قابل‌خواندن/قابل‌نوشتن **bool**. |
| [`has_series_lines`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | درست اگر نمودار خطوط سلسله داشته باشد. برای نمودارهای میله‌ای پشته‌ای و OfPie اعمال می‌شود.<br/>            قابل‌خواندن/قابل‌نوشتن **bool**. |
| [`overlap`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/overlap/) | مشخص می‌کند که میله‌ها و ستون‌ها تا چه میزان در چارت‌های ۲-بعدی هم‌پوشانی داشته باشند، به‌صورت درصد (از -100% تا 100%).<br/>             - -100%: بیشترین فاصله (میله‌ها کاملاً جدا هستند).<br/>             - 0%: میله‌ها به‌صورت کنار هم بدون هم‌پوشانی یا فاصله قرار می‌گیرند.<br/>             - 100%: بیشترین هم‌پوشانی (میله‌ها کاملاً بر هم گذاشته می‌شوند).<br/>             این ویژگی قابل‌خواندن/قابل‌نوشتن **int**. |
| [`second_pie_size`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | اندازه دایره یا میله دوم در نمودار پای-از-پای یا میله-از-پای را به‌عنوان درصدی از اندازه پای اول مشخص می‌کند (می‌تواند بین 5 تا 200 درصد باشد).<br/>            قابل‌خواندن/قابل‌نوشتن **int**. |
| [`pie_split_position`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | مقداری را مشخص می‌کند که برای تعیین نقاط داده‌ای که در دایره یا میله دوم یک نمودار پای-از-پای یا میله-از-پای قرار می‌گیرند، استفاده می‌شود. <br/>            همراه با ویژگی PieSplitBy استفاده می‌شود.<br/>            قابل‌خواندن/قابل‌نوشتن **float**. |
| [`pie_split_by`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | نحوه تعیین نقاط داده‌ای که در دایره یا میله دوم یک نمودار پای-از-پای یا میله-از-پای قرار می‌گیرند را مشخص می‌کند.<br/>            قابل‌خواندن/قابل‌نوشتن [`PieSplitType`](/slides/python-net/fa/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | اطلاعات تقسیم سفارشی برای یک نمودار پای-از-پای یا میله-از-پای با تقسیم سفارشی.<br/>            شامل نقاط داده‌ای است که باید در دایره یا میله دوم در یک نمودار پای-از-پای یا میله-از-پای کشیده شوند.<br/>            فقط-خواندنی [`IPieSplitCustomPointCollection`](/slides/python-net/fa/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`doughnut_hole_size`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | اندازه حفره در یک نمودار دونات را مشخص می‌کند (می‌تواند بین 10 تا 90 درصد از اندازه ناحیه رسم باشد).<br/>            قابل‌خواندن/قابل‌نوشتن **int**. |
| [`bubble_size_scale`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | عامل مقیاس برای نمودار حبابی را مشخص می‌کند (می‌تواند بین 0 تا 300 درصد از اندازه پیش‌فرض باشد).<br/>            قابل‌خواندن/قابل‌نوشتن **int**. |
| [`hi_low_lines_format`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | قالب HiLowLines را مشخص می‌کند. <br/>            HiLowLines با انواع نمودار HiLowClose، OpenHiLowClose، VolumeHiLowClose و VolumeOpenHiLowClose اعمال می‌شود. |
| [`bubble_size_representation`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | نحوه نمایش مقادیر اندازه حباب‌ها در نمودار حبابی را مشخص می‌کند.<br/>            قابل‌خواندن/قابل‌نوشتن [`BubbleSizeRepresentationType`](/slides/python-net/fa/aspose.slides.charts/bubblesizerepresentationtype). |
| [`chart`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

عنصری را که در اندیس مشخص قرار دارد دریافت می‌کند.

## شاخص

| نام | توضیح |
| :- | :- |
| [`[index]`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |

### توضیحات

1) خلاصه و توضیحات مربوط به ChartSeriesGroupCollection کلاس و CombinableSeriesTypesGroup enum را ببینید.
            2) گروهی از سلسله‌ها شامل برخی ویژگی‌های سلسله است که برای هر سلسله در گروه مشترک است ("ویژگی‌های گروه سلسله").
            "ویژگی‌های گروه سلسله" در ChartSeries کلاس قابل‌خواندن/قابل‌نوشتن است.
            هر یک از "ویژگی‌های گروه سلسله" می‌تواند یک بازتاب فقط-خواندنی در ChartSeries کلاس داشته باشد.

### همچنین ببینید
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)