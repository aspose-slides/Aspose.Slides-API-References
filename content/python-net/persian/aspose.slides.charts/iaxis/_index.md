---
title: IAxis class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.charts/iaxis/
---
## IAxis کلاس

شیئی که محور یک نمودار را نمایش می‌دهد را در بر می‌گیرد.

نوع IAxis اعضای زیر را در اختیار می‌گذارد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`axis_between_categories`](/slides/python-net/fa/aspose.slides.charts/iaxis/axis_between_categories/) | نمایانگر اینکه آیا محور مقدار بین محور دسته‌بندی در میان دسته‌ها عبور می‌کند.<br/>            این ویژگی فقط برای محورهاى دسته‌بندی اعمال می‌شود و برای نمودارهای سه‌بعدی کاربرد ندارد.<br/>            خواندن/نوشتن **bool**. |
| [`cross_at`](/slides/python-net/fa/aspose.slides.charts/iaxis/cross_at/) | نمایانگر نقطه‌ای بر محور که محور عمود بر آن عبور می‌کند.<br/>            خواندن/نوشتن **float**. |
| [`display_unit`](/slides/python-net/fa/aspose.slides.charts/iaxis/display_unit/) | مقدار مقیاس واحدهای نمایش برای محور مقدار را مشخص می‌کند.<br/>            خواندن/نوشتن [`DisplayUnitType`](/slides/python-net/fa/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/fa/aspose.slides.charts/iaxis/actual_max_value/) | حداکثر مقدار واقعی بر محور را مشخص می‌کند. پیش از آن برای دریافت مقدار واقعی متد IChart.ValidateChartLayout() را فراخوانی کنید. |
| [`actual_min_value`](/slides/python-net/fa/aspose.slides.charts/iaxis/actual_min_value/) | حداقل مقدار واقعی بر محور را مشخص می‌کند. پیش از آن برای دریافت مقدار واقعی متد IChart.ValidateChartLayout() را فراخوانی کنید. |
| [`actual_major_unit`](/slides/python-net/fa/aspose.slides.charts/iaxis/actual_major_unit/) | واحد اصلی واقعی محور را مشخص می‌کند. پیش از آن برای دریافت مقدار واقعی متد IChart.ValidateChartLayout() را فراخوانی کنید. |
| [`actual_minor_unit`](/slides/python-net/fa/aspose.slides.charts/iaxis/actual_minor_unit/) | واحد جزئی واقعی محور را مشخص می‌کند. پیش از آن برای دریافت مقدار واقعی متد IChart.ValidateChartLayout() را فراخوانی کنید. |
| [`actual_major_unit_scale`](/slides/python-net/fa/aspose.slides.charts/iaxis/actual_major_unit_scale/) | مقیاس واحد اصلی واقعی محور را مشخص می‌کند. پیش از آن برای دریافت مقدار واقعی متد IChart.ValidateChartLayout() را فراخوانی کنید. |
| [`actual_minor_unit_scale`](/slides/python-net/fa/aspose.slides.charts/iaxis/actual_minor_unit_scale/) | مقیاس واحد جزئی واقعی محور را مشخص می‌کند. پیش از آن برای دریافت مقدار واقعی متد IChart.ValidateChartLayout() را فراخوانی کنید. |
| [`is_automatic_max_value`](/slides/python-net/fa/aspose.slides.charts/iaxis/is_automatic_max_value/) | نمایانگر این که آیا مقدار حداکثر به‌صورت خودکار اختصاص داده می‌شود.<br/>             خواندن/نوشتن **bool**. |
| [`max_value`](/slides/python-net/fa/aspose.slides.charts/iaxis/max_value/) | نمایانگر مقدار حداکثر بر محور مقدار.<br/>             خواندن/نوشتن **float**. |
| [`minor_unit`](/slides/python-net/fa/aspose.slides.charts/iaxis/minor_unit/) | نمایانگر واحدهای جزئی برای محور تاریخ یا مقدار.<br/>             خواندن/نوشتن **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/fa/aspose.slides.charts/iaxis/is_automatic_minor_unit/) | نمایانگر این که آیا واحد جزئی محور به‌صورت خودکار اختصاص داده می‌شود.<br/>             خواندن/نوشتن **bool**. |
| [`major_unit`](/slides/python-net/fa/aspose.slides.charts/iaxis/major_unit/) | نمایانگر واحدهای اصلی برای محور تاریخ یا مقدار.<br/>             خواندن/نوشتن **float**. |
| [`is_automatic_major_unit`](/slides/python-net/fa/aspose.slides.charts/iaxis/is_automatic_major_unit/) | نمایانگر این که آیا واحد اصلی محور به‌صورت خودکار اختصاص داده می‌شود.<br/>            خواندن/نوشتن **bool**. |
| [`is_automatic_min_value`](/slides/python-net/fa/aspose.slides.charts/iaxis/is_automatic_min_value/) | نمایانگر این که آیا مقدار حداقل به‌صورت خودکار اختصاص داده می‌شود.<br/>             خواندن/نوشتن **bool**. |
| [`min_value`](/slides/python-net/fa/aspose.slides.charts/iaxis/min_value/) | نمایانگر مقدار حداقل بر محور مقدار.<br/>             خواندن/نوشتن **float**. |
| [`is_logarithmic`](/slides/python-net/fa/aspose.slides.charts/iaxis/is_logarithmic/) | نمایانگر این که آیا نوع مقیاس محور مقدار لگاریتمی است یا نه.<br/>             خواندن/نوشتن **bool**. |
| [`log_base`](/slides/python-net/fa/aspose.slides.charts/iaxis/log_base/) | پایه لگاریتمی را نمایان می‌کند. مقدار پیش‌فرض ۱۰ است.<br/>             خواندن/نوشتن **float**. |
| [`is_plot_order_reversed`](/slides/python-net/fa/aspose.slides.charts/iaxis/is_plot_order_reversed/) | نمایانگر اینکه آیا مایکروسافت پاورپوینت نقاط داده را از آخر به اول رسم می‌کند.<br/>             خواندن/نوشتن **bool**. |
| [`is_visible`](/slides/python-net/fa/aspose.slides.charts/iaxis/is_visible/) | نمایانگر این که آیا محور قابل مشاهده است.<br/>             خواندن/نوشتن **bool**. |
| [`major_tick_mark`](/slides/python-net/fa/aspose.slides.charts/iaxis/major_tick_mark/) | نوع علامت‌گذاری اصلی (major tick mark) برای محور مشخص شده را نمایان می‌کند.<br/>             خواندن/نوشتن [`TickMarkType`](/slides/python-net/fa/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/fa/aspose.slides.charts/iaxis/minor_tick_mark/) | نوع علامت‌گذاری جزئی (minor tick mark) برای محور مشخص شده را نمایان می‌کند.<br/>             خواندن/نوشتن [`TickMarkType`](/slides/python-net/fa/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/fa/aspose.slides.charts/iaxis/tick_label_position/) | موقعیت برچسب‌های علامت‌گذاری بر روی محور مشخص شده را نمایان می‌کند.<br/>             خواندن/نوشتن [`TickLabelPositionType`](/slides/python-net/fa/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/fa/aspose.slides.charts/iaxis/major_unit_scale/) | مقیاس واحد اصلی برای محور تاریخ را نمایان می‌کند.<br/>             خواندن/نوشتن [`TimeUnitType`](/slides/python-net/fa/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/fa/aspose.slides.charts/iaxis/minor_unit_scale/) | مقیاس واحد اصلی برای محور تاریخ را نمایان می‌کند.<br/>             خواندن/نوشتن [`TimeUnitType`](/slides/python-net/fa/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/fa/aspose.slides.charts/iaxis/base_unit_scale/) | کوچک‌ترین واحد زمان که بر روی محور تاریخ نمایش داده می‌شود را مشخص می‌کند.<br/>            خواندن/نوشتن [`TimeUnitType`](/slides/python-net/fa/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/fa/aspose.slides.charts/iaxis/minor_grid_lines_format/) | قالب خطوط شبکه جزئی بر روی محور نمودار را نمایان می‌کند.<br/>             فقط-خواندنی [`IChartLinesFormat`](/slides/python-net/fa/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/fa/aspose.slides.charts/iaxis/major_grid_lines_format/) | قالب خطوط شبکه اصلی بر روی محور نمودار را نمایان می‌کند.<br/>             فقط-خواندنی [`IChartLinesFormat`](/slides/python-net/fa/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/fa/aspose.slides.charts/iaxis/show_minor_grid_lines/) | نمایانگر اینکه آیا خطوط شبکه جزئی نمایش داده می‌شود.<br/>             فقط-خواندنی **bool**. |
| [`show_major_grid_lines`](/slides/python-net/fa/aspose.slides.charts/iaxis/show_major_grid_lines/) | نمایانگر اینکه آیا خطوط شبکه اصلی نمایش داده می‌شود.<br/>             فقط-خواندنی **bool**. |
| [`format`](/slides/python-net/fa/aspose.slides.charts/iaxis/format/) | قالب محور را نمایان می‌کند.<br/>             فقط-خواندنی [`IAxisFormat`](/slides/python-net/fa/aspose.slides.charts/iaxisformat). |
| [`title`](/slides/python-net/fa/aspose.slides.charts/iaxis/title/) | عنوان محور را دریافت می‌کند.<br/>             فقط-خواندنی [`IChartTitle`](/slides/python-net/fa/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/fa/aspose.slides.charts/iaxis/cross_type/) | نوع عبور (CrossType) بر روی محور مشخص شده که محور دیگر از آن عبور می‌کند را نمایان می‌کند.<br/>             خواندن/نوشتن [`CrossesType`](/slides/python-net/fa/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/fa/aspose.slides.charts/iaxis/position/) | موقعیت محور را نمایان می‌کند.<br/>             خواندن/نوشتن [`AxisPositionType`](/slides/python-net/fa/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/fa/aspose.slides.charts/iaxis/has_title/) | مشخص می‌کند آیا محور عنوان قابل مشاهده دارد یا خیر.<br/>            خواندن/نوشتن **bool**. |
| [`number_format`](/slides/python-net/fa/aspose.slides.charts/iaxis/number_format/) | رشته قالب‌بندی برای برچسب‌های محور را نمایان می‌کند.<br/>            خواندن/نوشتن **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/fa/aspose.slides.charts/iaxis/is_number_format_linked_to_source/) | نمایانگر این که آیا قالب با داده منبع پیوند خورده است.<br/>            خواندن/نوشتن **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/fa/aspose.slides.charts/iaxis/tick_label_rotation_angle/) | زاویه چرخش برچسب‌های علامت‌گذاری را نمایان می‌کند.<br/>            خواندن/نوشتن **float**. |
| [`tick_label_spacing`](/slides/python-net/fa/aspose.slides.charts/iaxis/tick_label_spacing/) | تعداد برچسب‌های علامت‌گذاری که بین برچسب‌های کشیده شده باید نادیده گرفته شوند را مشخص می‌کند.<br/>            خواندن/نوشتن **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/fa/aspose.slides.charts/iaxis/is_automatic_tick_label_spacing/) | مقدار فاصله خودکار برچسب‌های علامت‌گذاری را مشخص می‌کند. اگر false باشد: از ویژگی TickLabelSpacing استفاده کنید.<br/>            خواندن/نوشتن **bool**. |
| [`tick_marks_spacing`](/slides/python-net/fa/aspose.slides.charts/iaxis/tick_marks_spacing/) | تعداد علامت‌گذاری‌هایی که قبل از علامت بعدی باید نادیده گرفته شوند را مشخص می‌کند. برای محور دسته یا سری اعمال می‌شود.<br/>            خواندن/نوشتن **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/fa/aspose.slides.charts/iaxis/is_automatic_tick_marks_spacing/) | مقدار فاصله خودکار علامت‌گذاری‌ها را مشخص می‌کند. اگر false باشد: از ویژگی TickMarksSpacing استفاده کنید.<br/>            خواندن/نوشتن **bool**. |
| [`label_offset`](/slides/python-net/fa/aspose.slides.charts/iaxis/label_offset/) | فاصله برچسب‌ها از محور را مشخص می‌کند. برای محور دسته یا تاریخ اعمال می‌شود. مقدار باید بین ۰٪ تا ۱۰۰۰٪ باشد.<br/>            خواندن/نوشتن **int**. |
| [`category_axis_type`](/slides/python-net/fa/aspose.slides.charts/iaxis/category_axis_type/) | نوع محور دسته را مشخص می‌کند.<br/>            خواندن/نوشتن [`IAxis.category_axis_type`](/slides/python-net/fa/aspose.slides.charts/iaxis/category_axis_type). |
| [`aggregation_type`](/slides/python-net/fa/aspose.slides.charts/iaxis/aggregation_type/) | نوع تجمیع محور دسته (باینینگ) را نمایان می‌کند. برای دسته اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود. |
| [`bin_width`](/slides/python-net/fa/aspose.slides.charts/iaxis/bin_width/) | عرض باین را مشخص می‌کند زمانی که مقدار خصوصیت AggregationType بر روی AxisAggregationType.ByBinWidth تنظیم شده باشد.<br/>            برای محورهاى دسته اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود. |
| [`number_of_bins`](/slides/python-net/fa/aspose.slides.charts/iaxis/number_of_bins/) | تعداد باین‌ها را مشخص می‌کند زمانی که مقدار خصوصیت AggregationType بر روی AxisAggregationType.ByNumberOfBins تنظیم شده باشد.<br/>            برای محورهاى دسته اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود. |
| [`is_overflow_bin`](/slides/python-net/fa/aspose.slides.charts/iaxis/is_overflow_bin/) | مشخص می‌کند آیا باین سرریز اعمال می‌شود. برای تنظیم مقدار باین سرریز از IsAutomaticOverflowBin و OverflowBin استفاده کنید. |
| [`is_automatic_overflow_bin`](/slides/python-net/fa/aspose.slides.charts/iaxis/is_automatic_overflow_bin/) | مقدار خودکار باین سرریز را مشخص می‌کند. اگر false باشد: از خصوصیت OverflowBin استفاده کنید. |
| [`overflow_bin`](/slides/python-net/fa/aspose.slides.charts/iaxis/overflow_bin/) | مقدار سفارشی باین سرریز را مشخص می‌کند. زمانی که خصوصیت IsAutomaticOverflowBin برابر false و IsOverflowBin برابر true باشد، اعمال می‌شود. |
| [`is_underflow_bin`](/slides/python-net/fa/aspose.slides.charts/iaxis/is_underflow_bin/) | مشخص می‌کند آیا باین زیرسرریز اعمال می‌شود. برای تنظیم مقدار باین زیرسرریز از IsAutomaticUnderflowBin و UnderflowBin استفاده کنید. |
| [`is_automatic_underflow_bin`](/slides/python-net/fa/aspose.slides.charts/iaxis/is_automatic_underflow_bin/) | مقدار خودکار باین زیرسرریز را مشخص می‌کند. اگر false باشد: از خصوصیت UnderflowBin استفاده کنید. |
| [`underflow_bin`](/slides/python-net/fa/aspose.slides.charts/iaxis/underflow_bin/) | مقدار سفارشی باین زیرسرریز را مشخص می‌کند. زمانی که خصوصیت IsAutomaticUnderflowBin برابر false و IsUnderflowBin برابر true باشد، اعمال می‌شود. |
| [`text_format`](/slides/python-net/fa/aspose.slides.charts/iaxis/text_format/) |  |
| [`chart`](/slides/python-net/fa/aspose.slides.charts/iaxis/chart/) |  |
| [`slide`](/slides/python-net/fa/aspose.slides.charts/iaxis/slide/) |  |
| [`presentation`](/slides/python-net/fa/aspose.slides.charts/iaxis/presentation/) |  |

## متدها

| متد | توضیح |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/fa/aspose.slides.charts/iaxis/set_category_axis_type_automatically/#) | خصوصیت IAxis.CategoryAxisType را با مقداری که به‌صورت خودکار بر اساس داده‌های محور تعیین می‌شود تنظیم می‌کند. |

### موارد مرتبط
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)