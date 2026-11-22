---
title: DataLabel class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.charts/datalabel/
---
## کلاس DataLabel

نمایانگر برچسب‌های سری‌ها است.

نوع DataLabel اعضای زیر را در اختیار می‌گذارد:

## سازنده‌ها

| سازنده | توضیح |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/fa/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | یک نمونه جدید از کلاس DataLabel را ایجاد می‌کند. |

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`chart`](/slides/python-net/fa/aspose.slides.charts/datalabel/chart/) | نمودار والد را برمی‌گرداند.<br/>            فقط‌خواندنی [`IChart`](/slides/python-net/fa/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/fa/aspose.slides.charts/datalabel/is_visible/) | نادرست به این معنی است که برچسب داده قابل مشاهده نیست (و بنابراین تمام پرچم‌های Show*- (ShowValue, ...) نادرست هستند).<br/>            فقط‌خواندنی **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/fa/aspose.slides.charts/datalabel/text_frame_for_overriding/) | می‌تواند متن غنی قالب‌بندی‌شده‌ای را شامل شود. اگر این ویژگی None نباشد، این<br/>            مقدار متن قالب‌بندی‌شده متن تولید خودکار برچسب داده را نادیده می‌گیرد.<br/>            متن تولید خودکار برچسب داده به معنی متنی است که توسط ویژگی‌های ShowSeriesName،<br/>            ShowValue، ... مدیریت می‌شود و با ویژگی TextFormatManager.TextFormat قالب‌بندی می‌گردد.<br/>            فقط‌خواندنی [`ITextFrame`](/slides/python-net/fa/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/fa/aspose.slides.charts/datalabel/text_format/) | قالب متن را برمی‌گرداند.<br/>            فقط‌خواندنی [`IChartTextFormat`](/slides/python-net/fa/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/fa/aspose.slides.charts/datalabel/x/) | مختصات x عنوان را به عنوان کسری از عرض نمودار برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/نوشتن **float**. |
| [`y`](/slides/python-net/fa/aspose.slides.charts/datalabel/y/) | مختصات y عنوان را به عنوان کسری از ارتفاع نمودار برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/نوشتن **float**. |
| [`width`](/slides/python-net/fa/aspose.slides.charts/datalabel/width/) | عرض عنوان را به عنوان کسری از عرض نمودار برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/نوشتن **float**. |
| [`height`](/slides/python-net/fa/aspose.slides.charts/datalabel/height/) | ارتفاع عنوان را به عنوان کسری از ارتفاع نمودار برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/نوشتن **float**. |
| [`right`](/slides/python-net/fa/aspose.slides.charts/datalabel/right/) | راست.<br/>            فقط‌خواندنی **float**. |
| [`bottom`](/slides/python-net/fa/aspose.slides.charts/datalabel/bottom/) | پایین.<br/>            فقط‌خواندنی **float**. |
| [`data_label_format`](/slides/python-net/fa/aspose.slides.charts/datalabel/data_label_format/) | قالب برچسب داده را برمی‌گرداند.<br/>            فقط‌خواندنی [`IDataLabelFormat`](/slides/python-net/fa/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/fa/aspose.slides.charts/datalabel/value_from_cell/) | سلول داده کتاب‌کار را دریافت یا تنظیم می‌کند. اگر ویژگی IDataLabelFormat.ShowLabelValueFromCell برابر true باشد اعمال می‌شود. |
| [`label_shape_type`](/slides/python-net/fa/aspose.slides.charts/datalabel/label_shape_type/) | نوع شکل برچسب داده را دریافت یا تنظیم می‌کند.<br/>             اگر هیچ شکلی تعریف نشده باشد [`ShapeType.NOT_DEFINED`](/slides/python-net/fa/aspose.slides/shapetype/NOT_DEFINED) را برمی‌گرداند. |
| [`actual_x`](/slides/python-net/fa/aspose.slides.charts/datalabel/actual_x/) | موقعیت واقعی x (چپ) عنصر نمودار را نسبت به گوشه بالایی سمت چپ نمودار مشخص می‌کند.<br/>            قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را فراخوانی کنید. <br/>            خواندنی **float**. |
| [`actual_y`](/slides/python-net/fa/aspose.slides.charts/datalabel/actual_y/) | بالای واقعی عنصر نمودار را نسبت به گوشه بالایی سمت چپ نمودار مشخص می‌کند.<br/>            قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را فراخوانی کنید. <br/>            خواندنی **float**. |
| [`actual_width`](/slides/python-net/fa/aspose.slides.charts/datalabel/actual_width/) | عرض واقعی عنصر نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را فراخوانی کنید. <br/>            خواندنی **float**. |
| [`actual_height`](/slides/python-net/fa/aspose.slides.charts/datalabel/actual_height/) | ارتفاع واقعی عنصر نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را فراخوانی کنید. <br/>            خواندنی **float**. |
| [`slide`](/slides/python-net/fa/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/fa/aspose.slides.charts/datalabel/presentation/) |  |

## متدها

| متد | توضیح |
| :- | :- |
| [`hide(self)`](/slides/python-net/fa/aspose.slides.charts/datalabel/hide/#) | برچسب داده را با تنظیم تمام پرچم‌های Show*- (ShowValue, ...) به حالت نادرست مخفی می‌کند.<br/>            پس از این IsVisible نادرست خواهد بود. |
| [`get_actual_label_text(self)`](/slides/python-net/fa/aspose.slides.charts/datalabel/get_actual_label_text/#) | متن واقعی برچسب را بر اساس تنظیمات DataLabelFormat یا مقدار TextFrameForOverriding.Text برمی‌گرداند. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/fa/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | TextFrameForOverriding را با متن موجود در پارامتر "text" مقداردهی اولیه می‌کند.<br/>            اگر TextFrameForOverriding قبلاً مقداردهی شده باشد، صرفاً متن آن را تغییر می‌دهد. |

### موارد مرتبط
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)