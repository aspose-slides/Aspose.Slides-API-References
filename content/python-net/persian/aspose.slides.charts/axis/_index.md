---
title: Axis class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.charts/axis/
---
## کلاس Axis

شیئی را که نمایانگر محور نمودار است، در بر می‌گیرد.

نوع Axis اعضای زیر را ارائه می‌دهد:

## ویژگی‌ها

| خاصیت | توضیح |
| :- | :- |
| [`chart`](/slides/python-net/fa/aspose.slides.charts/axis/chart/) | نمودار والد را برمی‌گرداند.<br/>            فقط‌خواندنی [`IChart`](/slides/python-net/fa/aspose.slides.charts/ichart). |
| [`axis_between_categories`](/slides/python-net/fa/aspose.slides.charts/axis/axis_between_categories/) | مشخص می‌کند آیا محور مقدار، محور دسته‌بندی را بین دسته‌ها عبور می‌دهد.<br/>             این خصوصیت فقط برای محورهای دسته‌بندی اعمال می‌شود و برای نمودارهای سه‌بعدی کاربرد ندارد.<br/>             قابل‌خواندن/نوشتن **bool**. |
| [`category_axis_type`](/slides/python-net/fa/aspose.slides.charts/axis/category_axis_type/) | نوع محور دسته‌بندی را مشخص می‌کند.<br/>            قابل‌خواندن/نوشتن [`CategoryAxisType`](/slides/python-net/fa/aspose.slides.charts/categoryaxistype). |
| [`cross_at`](/slides/python-net/fa/aspose.slides.charts/axis/cross_at/) | نقطه‌ای روی محور را که محور عمود بر آن عبور می‌کند، نمایندگی می‌کند.<br/>             قابل‌خواندن/نوشتن **float**. |
| [`display_unit`](/slides/python-net/fa/aspose.slides.charts/axis/display_unit/) | مقدار مقیاس واحدهای نمایش برای محور مقدار را مشخص می‌کند.<br/>             قابل‌خواندن/نوشتن [`DisplayUnitType`](/slides/python-net/fa/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/fa/aspose.slides.charts/axis/actual_max_value/) | حداکثر مقدار واقعی روی محور را مشخص می‌کند. پیش از آن متد IChart.ValidateChartLayout() را فراخوانی کنید تا مقدار واقعی دریافت شود. |
| [`actual_min_value`](/slides/python-net/fa/aspose.slides.charts/axis/actual_min_value/) | حداقل مقدار واقعی روی محور را مشخص می‌کند. پیش از آن متد IChart.ValidateChartLayout() را فراخوانی کنید تا مقدار واقعی دریافت شود. |
| [`actual_major_unit`](/slides/python-net/fa/aspose.slides.charts/axis/actual_major_unit/) | واحد اصلی واقعی محور را مشخص می‌کند. پیش از آن متد IChart.ValidateChartLayout() را فراخوانی کنید تا مقدار واقعی دریافت شود. |
| [`actual_minor_unit`](/slides/python-net/fa/aspose.slides.charts/axis/actual_minor_unit/) | واحد فرعی واقعی محور را مشخص می‌کند. پیش از آن متد IChart.ValidateChartLayout() را فراخوانی کنید تا مقدار واقعی دریافت شود. |
| [`actual_major_unit_scale`](/slides/python-net/fa/aspose.slides.charts/axis/actual_major_unit_scale/) | مقیاس واحد اصلی واقعی محور را مشخص می‌کند. پیش از آن متد IChart.ValidateChartLayout() را فراخوانی کنید تا مقدار واقعی دریافت شود. |
| [`actual_minor_unit_scale`](/slides/python-net/fa/aspose.slides.charts/axis/actual_minor_unit_scale/) | مقیاس واحد فرعی واقعی محور را مشخص می‌کند. پیش از آن متد IChart.ValidateChartLayout() را فراخوانی کنید تا مقدار واقعی دریافت شود. |
| [`is_automatic_max_value`](/slides/python-net/fa/aspose.slides.charts/axis/is_automatic_max_value/) | مشخص می‌کند آیا مقدار حداکثر به‌صورت خودکار اختصاص داده می‌شود.<br/>             قابل‌خواندن/نوشتن **bool**. |
| [`max_value`](/slides/python-net/fa/aspose.slides.charts/axis/max_value/) | حداکثر مقدار روی محور مقدار را نماینده می‌شود.<br/>             قابل‌خواندن/نوشتن **float**. |
| [`minor_unit`](/slides/python-net/fa/aspose.slides.charts/axis/minor_unit/) | واحدهای فرعی برای محور تاریخ یا مقدار را نمایندگی می‌کند.<br/>             قابل‌خواندن/نوشتن **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/fa/aspose.slides.charts/axis/is_automatic_minor_unit/) | مشخص می‌کند آیا واحد فرعی محور به‌صورت خودکار اختصاص داده می‌شود.<br/>             قابل‌خواندن/نوشتن **bool**. |
| [`major_unit`](/slides/python-net/fa/aspose.slides.charts/axis/major_unit/) | واحدهای اصلی برای محور تاریخ یا مقدار را نمایندگی می‌کند.<br/>             قابل‌خواندن/نوشتن **float**. |
| [`is_automatic_major_unit`](/slides/python-net/fa/aspose.slides.charts/axis/is_automatic_major_unit/) | مشخص می‌کند آیا واحد اصلی محور به‌صورت خودکار اختصاص داده می‌شود.<br/>            قابل‌خواندن/نوشتن **bool**. |
| [`is_automatic_min_value`](/slides/python-net/fa/aspose.slides.charts/axis/is_automatic_min_value/) | مشخص می‌کند آیا مقدار حداقل به‌صورت خودکار اختصاص داده می‌شود.<br/>             قابل‌خواندن/نوشتن **bool**. |
| [`min_value`](/slides/python-net/fa/aspose.slides.charts/axis/min_value/) | حداقل مقدار روی محور مقدار را نماینده می‌شود.<br/>             قابل‌خواندن/نوشتن **float**. |
| [`is_logarithmic`](/slides/python-net/fa/aspose.slides.charts/axis/is_logarithmic/) | مشخص می‌کند نوع مقیاس محور مقدار لگاریتمی است یا نه.<br/>             قابل‌خواندن/نوشتن **bool**. |
| [`log_base`](/slides/python-net/fa/aspose.slides.charts/axis/log_base/) | پایهٔ لگاریتمی را نمایندگی می‌کند. مقدار پیش‌فرض ۱۰ است.<br/>             قابل‌خواندن/نوشتن **float**. |
| [`is_plot_order_reversed`](/slides/python-net/fa/aspose.slides.charts/axis/is_plot_order_reversed/) | مشخص می‌کند آیا MS PowerPoint نقاط داده را از آخر به اول رسم می‌کند.<br/>             قابل‌خواندن/نوشتن **bool**. |
| [`is_visible`](/slides/python-net/fa/aspose.slides.charts/axis/is_visible/) | مشخص می‌کند آیا محور قابل مشاهده است.<br/>             قابل‌خواندن/نوشتن **bool**. |
| [`major_tick_mark`](/slides/python-net/fa/aspose.slides.charts/axis/major_tick_mark/) | نوع علامت تیک اصلی برای محور مشخص‌شده را نمایندگی می‌کند.<br/>             قابل‌خواندن/نوشتن [`TickMarkType`](/slides/python-net/fa/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/fa/aspose.slides.charts/axis/minor_tick_mark/) | نوع علامت تیک فرعی برای محور مشخص‌شده را نمایندگی می‌کند.<br/>             قابل‌خواندن/نوشتن [`TickMarkType`](/slides/python-net/fa/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/fa/aspose.slides.charts/axis/tick_label_position/) | موقعیت برچسب‌های علامت تیک روی محور مشخص‌شده را نمایندگی می‌کند.<br/>             قابل‌خواندن/نوشتن [`TickLabelPositionType`](/slides/python-net/fa/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/fa/aspose.slides.charts/axis/major_unit_scale/) | مقیاس واحد اصلی برای محور تاریخ را نمایندگی می‌کند.<br/>             قابل‌خواندن/نوشتن [`TimeUnitType`](/slides/python-net/fa/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/fa/aspose.slides.charts/axis/minor_unit_scale/) | مقیاس واحد اصلی برای محور تاریخ را نمایندگی می‌کند.<br/>             قابل‌خواندن/نوشتن [`TimeUnitType`](/slides/python-net/fa/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/fa/aspose.slides.charts/axis/base_unit_scale/) | کوچک‌ترین واحد زمان که روی محور تاریخ نمایش داده می‌شود را مشخص می‌کند.<br/>            قابل‌خواندن/نوشتن [`TimeUnitType`](/slides/python-net/fa/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/fa/aspose.slides.charts/axis/minor_grid_lines_format/) | قالب خطوط شبکه فرعی روی محور نمودار را نمایند می‌کند.<br/>             فقط‌خواندنی [`IChartLinesFormat`](/slides/python-net/fa/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/fa/aspose.slides.charts/axis/major_grid_lines_format/) | قالب خطوط شبکه اصلی روی محور نمودار را نمایند می‌کند.<br/>             فقط‌خواندنی [`IChartLinesFormat`](/slides/python-net/fa/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/fa/aspose.slides.charts/axis/show_minor_grid_lines/) | برای مخفی‌سازی خط شبکه فرعی، مقدار MinorGridLinesFormat.Line.FillFormat.FillType را به FillType.NoFill تنظیم کنید.<br/>            فقط‌خواندنی **bool**. |
| [`show_major_grid_lines`](/slides/python-net/fa/aspose.slides.charts/axis/show_major_grid_lines/) | برای مخفی‌سازی خط شبکه اصلی، مقدار MajorGridLinesFormat.Line.FillFormat.FillType را به FillType.NoFill تنظیم کنید.<br/>            فقط‌خواندنی **bool**. |
| [`format`](/slides/python-net/fa/aspose.slides.charts/axis/format/) | قالب محور را نمایندگی می‌کند.<br/>             فقط‌خواندنی [`IAxisFormat`](/slides/python-net/fa/aspose.slides.charts/iaxisformat). |
| [`text_format`](/slides/python-net/fa/aspose.slides.charts/axis/text_format/) | قالب متن را نمایندگی می‌کند.<br/>             فقط‌خواندنی [`IChartTextFormat`](/slides/python-net/fa/aspose.slides.charts/icharttextformat). |
| [`title`](/slides/python-net/fa/aspose.slides.charts/axis/title/) | عنوان محور را دریافت می‌کند.<br/>             فقط‌خواندنی [`IChartTitle`](/slides/python-net/fa/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/fa/aspose.slides.charts/axis/cross_type/) | نوع CrossType روی محور مشخص‌شده که محور دیگر از آن عبور می‌کند را نمایندگی می‌کند.<br/>             قابل‌خواندن/نوشتن [`CrossesType`](/slides/python-net/fa/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/fa/aspose.slides.charts/axis/position/) | موقعیت محور را نمایندگی می‌کند.<br/>             قابل‌خواندن/نوشتن [`AxisPositionType`](/slides/python-net/fa/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/fa/aspose.slides.charts/axis/has_title/) | مشخص می‌کند آیا محور عنوان قابل مشاهده دارد.<br/>            قابل‌خواندن/نوشتن **bool**. |
| [`number_format`](/slides/python-net/fa/aspose.slides.charts/axis/number_format/) | رشتهٔ قالب برای برچسب‌های محور را نمایندگی می‌کند.<br/>            قابل‌خواندن/نوشتن **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/fa/aspose.slides.charts/axis/is_number_format_linked_to_source/) | مشخص می‌کند آیا قالب به داده منبع پیوند خورده است.<br/>            قابل‌خواندن/نوشتن **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/fa/aspose.slides.charts/axis/tick_label_rotation_angle/) | زاویهٔ چرخش برچسب‌های تیک را نمایندگی می‌کند.<br/>            قابل‌خواندن/نوشتن **float**. |
| [`tick_label_spacing`](/slides/python-net/fa/aspose.slides.charts/axis/tick_label_spacing/) | تعداد برچسب‌های تیکی که بین برچسب‌های رسم‌شده نادیده گرفته می‌شود را مشخص می‌کند. برای محور دسته یا سری اعمال می‌شود.<br/>            قابل‌خواندن/نوشتن **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/fa/aspose.slides.charts/axis/is_automatic_tick_label_spacing/) | مقدار فاصلهٔ خودکار برچسب‌های تیک را مشخص می‌کند. اگر false باشد: از ویژگی TickLabelSpacing استفاده کنید.<br/>            قابل‌خواندن/نوشتن **bool**. |
| [`tick_marks_spacing`](/slides/python-net/fa/aspose.slides.charts/axis/tick_marks_spacing/) | تعداد علامت‌های تیکی که قبل از علامت بعدی باید نادیده گرفته شوند را مشخص می‌کند.<br/>            برای محور دسته یا سری اعمال می‌شود.<br/>            قابل‌خواندن/نوشتن **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/fa/aspose.slides.charts/axis/is_automatic_tick_marks_spacing/) | مقدار فاصلهٔ خودکار علامت‌های تیک را مشخص می‌کند. اگر false باشد: از ویژگی TickMarksSpacing استفاده کنید.<br/>            قابل‌خواندن/نوشتن **bool**. |
| [`label_offset`](/slides/python-net/fa/aspose.slides.charts/axis/label_offset/) | فاصلهٔ برچسب‌ها از محور را مشخص می‌کند. برای محور دسته یا تاریخ اعمال می‌شود. مقدار باید بین ۰٪ و ۱۰۰۰٪ باشد.<br/>            قابل‌خواندن/نوشتن **int**. |
| [`aggregation_type`](/slides/python-net/fa/aspose.slides.charts/axis/aggregation_type/) | نوع تجمیع محور دسته (بینه‌بندی) را نمایندگی می‌کند. برای دسته اعمال می‌شود. فقط با سری Histogram یا HistogramPareto استفاده می‌شود. |
| [`bin_width`](/slides/python-net/fa/aspose.slides.charts/axis/bin_width/) | عرض بین‌ را هنگامی که مقدار ویژگی AggregationType برابر AxisAggregationType.ByBinWidth تنظیم شده باشد، مشخص می‌کند.<br/>            برای محورهای دسته اعمال می‌شود. فقط با سری Histogram یا HistogramPareto استفاده می‌شود. |
| [`number_of_bins`](/slides/python-net/fa/aspose.slides.charts/axis/number_of_bins/) | تعداد بین‌ها را هنگامی که مقدار ویژگی AggregationType برابر AxisAggregationType.ByNumberOfBins تنظیم شده باشد، مشخص می‌کند.<br/>            برای محورهای دسته اعمال می‌شود. فقط با سری Histogram یا HistogramPareto استفاده می‌شود. |
| [`is_overflow_bin`](/slides/python-net/fa/aspose.slides.charts/axis/is_overflow_bin/) | مشخص می‌کند آیا بین‌ سرریز اعمال می‌شود. برای تنظیم مقدار بین‌ سرریز از IsAutomaticOverflowBin و OverflowBin استفاده کنید. |
| [`is_automatic_overflow_bin`](/slides/python-net/fa/aspose.slides.charts/axis/is_automatic_overflow_bin/) | مقدار خودکار بین‌ سرریز را مشخص می‌کند. اگر false باشد: از ویژگی OverflowBin استفاده کنید. |
| [`overflow_bin`](/slides/python-net/fa/aspose.slides.charts/axis/overflow_bin/) | مقدار سفارشی بین‌ سرریز را مشخص می‌کند. زمانی اعمال می‌شود که ویژگی IsAutomaticOverflowBin برابر false و ویژگی IsOverflowBin برابر true باشد. |
| [`is_underflow_bin`](/slides/python-net/fa/aspose.slides.charts/axis/is_underflow_bin/) | مشخص می‌کند آیا بین‌ زیرریز اعمال می‌شود. برای تنظیم مقدار بین‌ زیرریز از IsAutomaticUnderflowBin و UnderflowBin استفاده کنید. |
| [`is_automatic_underflow_bin`](/slides/python-net/fa/aspose.slides.charts/axis/is_automatic_underflow_bin/) | مقدار خودکار بین‌ زیرریز را مشخص می‌کند. اگر false باشد: از ویژگی UnderflowBin استفاده کنید. |
| [`underflow_bin`](/slides/python-net/fa/aspose.slides.charts/axis/underflow_bin/) | مقدار سفارشی بین‌ زیرریز را مشخص می‌کند. زمانی اعمال می‌شود که ویژگی IsAutomaticUnderflowBin برابر false و ویژگی IsUnderflowBin برابر true باشد. |
| [`slide`](/slides/python-net/fa/aspose.slides.charts/axis/slide/) |  |
| [`presentation`](/slides/python-net/fa/aspose.slides.charts/axis/presentation/) |  |

## متدها

| متد | توضیح |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/fa/aspose.slides.charts/axis/set_category_axis_type_automatically/#) | ویژگی IAxis.CategoryAxisType را با مقداری که به‌صورت خودکار بر اساس داده‌های محور تعیین می‌شود، تنظیم می‌کند. |

### همچنین ببینید
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)