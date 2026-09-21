---
title: DataLabel class
second_title: Aspose.Slides برای Python از طریق مرجع API .NET
description: 
type: docs
url: /fa/aspose.slides.charts/datalabel/
---
## کلاس DataLabel

یک برچسب‌های یک سری را نمایان می‌کند.

نوع DataLabel اعضای زیر را در اختیار می‌گذارد:

## سازندگان

| سازنده | شرح |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/fa/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | یک نمونه جدید از کلاس DataLabel ایجاد می‌کند. |

## ویژگی‌ها

| ویژگی | شرح |
| :- | :- |
| [`chart`](/slides/python-net/fa/aspose.slides.charts/datalabel/chart/) | نمودار والد را برمی‌گرداند.<br/>            فقط خواندنی [`IChart`](/slides/python-net/fa/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/fa/aspose.slides.charts/datalabel/is_visible/) | مقدار False به این معناست که برچسب داده قابل مشاهده نیست (و بنابراین تمام پرچم‌های Show* (ShowValue, ...) نیز False هستند).<br/>            فقط خواندنی **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/fa/aspose.slides.charts/datalabel/text_frame_for_overriding/) | می‌تواند متن قالب‌بندی شده غنی را در خود داشته باشد. اگر این ویژگی None نباشد، پس این <br/>            مقدار متن قالب‌بندی شده متن خودکار تولید شده برچسب داده را بازنویسی می‌کند.<br/>            متن خودکار تولید شده برچسب داده به متنی گفته می‌شود که توسط ویژگی‌های ShowSeriesName، <br/>            ShowValue، ... مدیریت می‌شود و با ویژگی TextFormatManager.TextFormat قالب‌بندی می‌شود.<br/>            فقط خواندنی [`ITextFrame`](/slides/python-net/fa/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/fa/aspose.slides.charts/datalabel/text_format/) | قالب متن را برمی‌گرداند.<br/>            فقط خواندنی [`IChartTextFormat`](/slides/python-net/fa/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/fa/aspose.slides.charts/datalabel/x/) | مختصات x عنوان را به عنوان کسری از عرض نمودار برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن **float**. |
| [`y`](/slides/python-net/fa/aspose.slides.charts/datalabel/y/) | مختصات y عنوان را به عنوان کسری از ارتفاع نمودار برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن **float**. |
| [`width`](/slides/python-net/fa/aspose.slides.charts/datalabel/width/) | عرض عنوان را به عنوان کسری از عرض نمودار برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن **float**. |
| [`height`](/slides/python-net/fa/aspose.slides.charts/datalabel/height/) | ارتفاع عنوان را به عنوان کسری از ارتفاع نمودار برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن **float**. |
| [`right`](/slides/python-net/fa/aspose.slides.charts/datalabel/right/) | راست.<br/>            فقط خواندنی **float**. |
| [`bottom`](/slides/python-net/fa/aspose.slides.charts/datalabel/bottom/) | پایین.<br/>            فقط خواندنی **float**. |
| [`data_label_format`](/slides/python-net/fa/aspose.slides.charts/datalabel/data_label_format/) | قالب برچسب داده را برمی‌گرداند.<br/>            فقط خواندنی [`IDataLabelFormat`](/slides/python-net/fa/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/fa/aspose.slides.charts/datalabel/value_from_cell/) | سلول داده کتاب کار را برمی‌گیرد یا تنظیم می‌کند. در صورتی که ویژگی IDataLabelFormat.ShowLabelValueFromCell برابر true باشد اعمال می‌شود. |
| [`actual_x`](/slides/python-net/fa/aspose.slides.charts/datalabel/actual_x/) | موقعیت واقعی x (چپ) عنصر نمودار را نسبت به گوشهٔ بالا-چپ نمودار مشخص می‌کند.<br/>            پیش از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را فراخوانی کنید. <br/>            خواندنی **float**. |
| [`actual_y`](/slides/python-net/fa/aspose.slides.charts/datalabel/actual_y/) | بالای واقعی عنصر نمودار را نسبت به گوشهٔ بالا-چپ نمودار مشخص می‌کند.<br/>            پیش از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را فراخوانی کنید. <br/>            خواندنی **float**. |
| [`actual_width`](/slides/python-net/fa/aspose.slides.charts/datalabel/actual_width/) | عرض واقعی عنصر نمودار را مشخص می‌کند. پیش از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را فراخوانی کنید. <br/>            خواندنی **float**. |
| [`actual_height`](/slides/python-net/fa/aspose.slides.charts/datalabel/actual_height/) | ارتفاع واقعی عنصر نمودار را مشخص می‌کند. پیش از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را فراخوانی کنید. <br/>            خواندنی **float**. |
| [`slide`](/slides/python-net/fa/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/fa/aspose.slides.charts/datalabel/presentation/) |  |

## متدها

| متد | شرح |
| :- | :- |
| [`hide(self)`](/slides/python-net/fa/aspose.slides.charts/datalabel/hide/#) | برچسب داده را با تنظیم تمام پرچم‌های Show* (ShowValue, ...) به وضعیت false مخفی می‌کند.<br/>            پس از این، IsVisible مقدار false خواهد داشت. |
| [`get_actual_label_text(self)`](/slides/python-net/fa/aspose.slides.charts/datalabel/get_actual_label_text/#) | متن واقعی برچسب را بر اساس تنظیمات DataLabelFormat یا مقدار TextFrameForOverriding.Text برمی‌گرداند. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/fa/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | TextFrameForOverriding را با متن موجود در پارامتر "text" مقداردهی اولیه می‌کند.<br/>            اگر TextFrameForOverriding از پیش مقداردهی شده باشد، صرفاً متن آن را تغییر می‌دهد. |

### مراجع
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)