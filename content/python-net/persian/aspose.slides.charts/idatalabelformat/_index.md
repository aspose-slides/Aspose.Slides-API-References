---
title: IDataLabelFormat class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat کلاس

گزینه‌های قالب‌بندی برای DataLabel را نشان می‌دهد.

نوع IDataLabelFormat اعضای زیر را در اختیار می‌گذارد:

## خواص

| Property | Description |
| :- | :- |
| [`is_number_format_linked_to_source`](/slides/python-net/fa/aspose.slides.charts/idatalabelformat/is_number_format_linked_to_source/) | خواندنی/نوشتنی **bool**. |
| [`number_format`](/slides/python-net/fa/aspose.slides.charts/idatalabelformat/number_format/) | رشتهٔ قالب برای شیء DataLabels را نمایش می‌دهد.<br/>            خواندنی/نوشتنی **str**. |
| [`format`](/slides/python-net/fa/aspose.slides.charts/idatalabelformat/format/) | قالب برچسب داده را نمایش می‌دهد.<br/>            فقط-خواندنی [`IFormat`](/slides/python-net/fa/aspose.slides.charts/iformat). |
| [`position`](/slides/python-net/fa/aspose.slides.charts/idatalabelformat/position/) | موقعیت برچسب داده را نمایش می‌دهد.<br/>            خواندنی/نوشتنی [`LegendDataLabelPosition`](/slides/python-net/fa/aspose.slides.charts/legenddatalabelposition). |
| [`show_legend_key`](/slides/python-net/fa/aspose.slides.charts/idatalabelformat/show_legend_key/) | رفتار نمایش کلید افسانه برچسب دادهٔ یک نمودار مشخص را نمایش می‌دهد. <br/>            True اگر کلید افسانه برچسب داده قابل مشاهده باشد.<br/>            خواندنی/نوشتنی **bool**. |
| [`show_value`](/slides/python-net/fa/aspose.slides.charts/idatalabelformat/show_value/) | رفتار نمایش مقدار درصد برچسب دادهٔ یک نمودار مشخص را نمایش می‌دهد. <br/>            True مقدار درصد را نمایش می‌دهد. False برای پنهان کردن.<br/>            خواندنی/نوشتنی **bool**. |
| [`show_category_name`](/slides/python-net/fa/aspose.slides.charts/idatalabelformat/show_category_name/) | رفتار نمایش نام دستهٔ برچسب دادهٔ یک نمودار مشخص را نمایش می‌دهد.<br/>            True برای نمایش نام دستهٔ برچسب‌های داده در یک نمودار. False برای پنهان کردن.<br/>            خواندنی/نوشتنی **bool**. |
| [`show_series_name`](/slides/python-net/fa/aspose.slides.charts/idatalabelformat/show_series_name/) | یک Boolean را برمی‌گرداند یا تنظیم می‌کند تا رفتار نمایش نام سری برای برچسب‌های داده در یک نمودار را نشان دهد. <br/>            True برای نمایش نام سری. False برای پنهان کردن.<br/>            خواندنی/نوشتنی **bool**. |
| [`show_percentage`](/slides/python-net/fa/aspose.slides.charts/idatalabelformat/show_percentage/) | رفتار نمایش مقدار درصد برچسب دادهٔ یک نمودار مشخص را نمایش می‌دهد. <br/>            True مقدار درصد را نمایش می‌دهد. False برای پنهان کردن.<br/>            خواندنی/نوشتنی **bool**. |
| [`show_bubble_size`](/slides/python-net/fa/aspose.slides.charts/idatalabelformat/show_bubble_size/) | رفتار نمایش مقدار اندازه حباب برچسب دادهٔ یک نمودار مشخص را نمایش می‌دهد. <br/>            True مقدار اندازه حباب را نمایش می‌دهد. False برای پنهان کردن.<br/>            خواندنی/نوشتنی **bool**. |
| [`show_leader_lines`](/slides/python-net/fa/aspose.slides.charts/idatalabelformat/show_leader_lines/) | رفتار نمایش خطوط راهنما برچسب دادهٔ یک نمودار مشخص را نمایش می‌دهد. <br/>            True خطوط راهنما را نمایش می‌دهد. False برای پنهان کردن.<br/>            خواندنی/نوشتنی **bool**. |
| [`show_label_as_data_callout`](/slides/python-net/fa/aspose.slides.charts/idatalabelformat/show_label_as_data_callout/) | مشخص می‌کند که آیا برچسب دادهٔ یک نمودار مشخص به‌صورت فراخوان داده یا به‌صورت برچسب داده نمایش داده شود.<br/>            <br/>            اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، سپس این<br/>            ویژگی مقدار پیش‌فرض ویژگی ShowLabelAsDataCallout را برای داده‌های جدید<br/>            برچسب‌های موجود در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند.<br/>            تنظیم این ویژگی با مقدار، همچنین مقدار را برای ویژگی ShowLabelAsDataCallout<br/>            برای تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند<br/>            (i.e. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" باعث می‌شود<br/>            تمام DataLabels[i].ShowLabelAsDataCallout برابر با val می‌شود). |
| [`show_label_value_from_cell`](/slides/python-net/fa/aspose.slides.charts/idatalabelformat/show_label_value_from_cell/) | رفتار نمایش مقدار سلول برچسب دادهٔ یک نمودار مشخص را نمایش می‌دهد. <br/>            True مقدار سلول را نمایش می‌دهد. False برای پنهان کردن.<br/>            خواندنی/نوشتنی **bool**. |
| [`separator`](/slides/python-net/fa/aspose.slides.charts/idatalabelformat/separator/) | یک Variant را تنظیم یا برمی‌گرداند که جداکننده استفاده شده برای برچسب‌های داده در یک نمودار را نشان می‌دهد.<br/>            خواندنی/نوشتنی **str**. |
| [`text_format`](/slides/python-net/fa/aspose.slides.charts/idatalabelformat/text_format/) |  |
| [`chart`](/slides/python-net/fa/aspose.slides.charts/idatalabelformat/chart/) |  |
| [`slide`](/slides/python-net/fa/aspose.slides.charts/idatalabelformat/slide/) |  |
| [`presentation`](/slides/python-net/fa/aspose.slides.charts/idatalabelformat/presentation/) |  |


### موارد مرتبط
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)