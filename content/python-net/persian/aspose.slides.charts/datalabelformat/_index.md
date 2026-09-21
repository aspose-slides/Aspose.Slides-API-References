---
title: DataLabelFormat class
second_title: مرجع API Aspose.Slides برای پایتون از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat کلاس

نمایانگر گزینه‌های قالب‌بندی برای DataLabel.

**ارث‌برداری:**[`DataLabelFormat`](/slides/python-net/fa/aspose.slides.charts/datalabelformat) → [`PVIObject`](/slides/python-net/fa/aspose.slides/pviobject)

نوع DataLabelFormat اعضای زیر را نمایان می‌کند:

## ویژگی‌ها

| Property | Description |
| :- | :- |
| [`is_number_format_linked_to_source`](/slides/python-net/fa/aspose.slides.charts/datalabelformat/is_number_format_linked_to_source/) | خواندن/نوشتن **bool**. |
| [`number_format`](/slides/python-net/fa/aspose.slides.charts/datalabelformat/number_format/) | نمایانگر رشتهٔ قالب برای شی DataLabels.<br/>            خواندن/نوشتن **str**. |
| [`format`](/slides/python-net/fa/aspose.slides.charts/datalabelformat/format/) | نمایانگر قالب برچسب داده.<br/>            فقط‌خواندنی [`IFormat`](/slides/python-net/fa/aspose.slides.charts/iformat). |
| [`position`](/slides/python-net/fa/aspose.slides.charts/datalabelformat/position/) | نمایانگر موقعیت برچسب داده.<br/>            خواندن/نوشتن [`LegendDataLabelPosition`](/slides/python-net/fa/aspose.slides.charts/legenddatalabelposition). |
| [`show_legend_key`](/slides/python-net/fa/aspose.slides.charts/datalabelformat/show_legend_key/) | نمایانگر رفتار نمایش کلید افسانهٔ برچسب دادهٔ نمودار مشخص.<br/>            درست اگر کلید افسانهٔ برچسب داده قابل مشاهده باشد.<br/>            خواندن/نوشتن **bool**. |
| [`show_value`](/slides/python-net/fa/aspose.slides.charts/datalabelformat/show_value/) | نمایانگر رفتار نمایش مقدار درصد برچسب دادهٔ نمودار مشخص.<br/>            درست مقدار درصد را نمایش می‌دهد. غلط برای پنهان‌سازی.<br/>            خواندن/نوشتن **bool**. |
| [`show_category_name`](/slides/python-net/fa/aspose.slides.charts/datalabelformat/show_category_name/) | نمایانگر رفتار نمایش نام دسته‌بندی برچسب دادهٔ نمودار مشخص.<br/>            درست برای نمایش نام دسته‌بندی برای برچسب‌های داده در یک نمودار. غلط برای پنهان‌سازی.<br/>            خواندن/نوشتن **bool**. |
| [`show_series_name`](/slides/python-net/fa/aspose.slides.charts/datalabelformat/show_series_name/) | باز می‌گرداند یا تنظیم می‌کند یک Boolean برای نشان دادن رفتار نمایش نام سری برای برچسب‌های داده در یک نمودار.<br/>            درست برای نمایش نام سری. غلط برای پنهان‌سازی.<br/>            خواندن/نوشتن **bool**. |
| [`show_percentage`](/slides/python-net/fa/aspose.slides.charts/datalabelformat/show_percentage/) | نمایانگر رفتار نمایش مقدار درصد برچسب دادهٔ نمودار مشخص.<br/>            درست مقدار درصد را نمایش می‌دهد. غلط برای پنهان‌سازی.<br/>            خواندن/نوشتن **bool**. |
| [`show_bubble_size`](/slides/python-net/fa/aspose.slides.charts/datalabelformat/show_bubble_size/) | نمایانگر رفتار نمایش مقدار اندازهٔ حباب برچسب دادهٔ نمودار مشخص.<br/>            درست مقدار اندازهٔ حباب را نمایش می‌دهد. غلط برای پنهان‌سازی.<br/>            خواندن/نوشتن **bool**. |
| [`show_leader_lines`](/slides/python-net/fa/aspose.slides.charts/datalabelformat/show_leader_lines/) | نمایانگر رفتار نمایش خطوط رهبری برچسب دادهٔ نمودار مشخص.<br/>            درست خطوط رهبری را نمایش می‌دهد. غلط برای پنهان‌سازی.<br/>            خواندن/نوشتن **bool**. |
| [`show_label_value_from_cell`](/slides/python-net/fa/aspose.slides.charts/datalabelformat/show_label_value_from_cell/) | نمایانگر رفتار نمایش مقدار سلول برچسب دادهٔ نمودار مشخص.<br/>            درست مقدار سلول را نمایش می‌دهد. غلط برای پنهان‌سازی.<br/>            خواندن/نوشتن **bool**. |
| [`show_label_as_data_callout`](/slides/python-net/fa/aspose.slides.charts/datalabelformat/show_label_as_data_callout/) | مشخص می‌کند که آیا برچسب دادهٔ نمودار مشخص به عنوان فراخوان داده یا به عنوان برچسب داده نمایش داده شود.<br/>            <br/>            اگر والد این شی DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این خاصیت مقدار پیش‌فرض ویژگی ShowLabelAsDataCallout را برای برچسب‌های دادهٔ جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این خاصیت با مقدار، همچنین این مقدار را به ویژگی ShowLabelAsDataCallout برای تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (به عنوان مثال "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" باعث می‌شود تمام DataLabels[i].ShowLabelAsDataCallout برابر با val باشد). |
| [`separator`](/slides/python-net/fa/aspose.slides.charts/datalabelformat/separator/) | تنظیم یا بازگرداندن یک Variant که نشان‌دهنده جداکننده استفاده‌شده برای برچسب‌های داده در یک نمودار است.<br/>            خواندن/نوشتن **str**. |
| [`text_format`](/slides/python-net/fa/aspose.slides.charts/datalabelformat/text_format/) | باز می‌گرداند قالب متن نمودار.<br/>            فقط‌خواندنی [`IChartTextFormat`](/slides/python-net/fa/aspose.slides.charts/icharttextformat). |
| [`chart`](/slides/python-net/fa/aspose.slides.charts/datalabelformat/chart/) | باز می‌گرداند نمودار.<br/>            فقط‌خواندنی [`IChart`](/slides/python-net/fa/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/fa/aspose.slides.charts/datalabelformat/slide/) |  |
| [`presentation`](/slides/python-net/fa/aspose.slides.charts/datalabelformat/presentation/) |  |

### مراجع
* کلاس [`DataLabelFormat`](/slides/python-net/fa/aspose.slides.charts/datalabelformat)
* کلاس [`PVIObject`](/slides/python-net/fa/aspose.slides/pviobject)
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)