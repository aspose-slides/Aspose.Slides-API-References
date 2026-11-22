---
title: IDataLabel class
second_title: Aspose.Slides برای Python از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides.charts/idatalabel/
---
## IDataLabel کلاس

نمایانگر برچسب‌های سری است.

نوع IDataLabel اعضای زیر را ارائه می‌دهد:

## ویژگی‌ها

| Property | Description |
| :- | :- |
| [`is_visible`](/slides/python-net/fa/aspose.slides.charts/idatalabel/is_visible/) | مقدار False به این معنی است که برچسب داده قابل مشاهده نیست (و بنابراین تمام پرچم‌های Show*-flags (ShowValue, ...) برابر با false هستند).<br/>            فقط-خواندنی **bool**. |
| [`data_label_format`](/slides/python-net/fa/aspose.slides.charts/idatalabel/data_label_format/) | قالب برچسب داده را برمی‌گرداند.<br/>            فقط-خواندنی [`IDataLabelFormat`](/slides/python-net/fa/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/fa/aspose.slides.charts/idatalabel/value_from_cell/) | سلول دادهٔ کتاب کار را دریافت یا تنظیم می‌کند. در صورتی که ویژگی IDataLabelFormat.ShowLabelValueFromCell برابر با true باشد اعمال می‌شود. |
| [`label_shape_type`](/slides/python-net/fa/aspose.slides.charts/idatalabel/label_shape_type/) | نوع شکل برچسب داده را دریافت یا تنظیم می‌کند.<br/>             اگر شکلی تعریف نشده باشد [`ShapeType.NOT_DEFINED`](/slides/python-net/fa/aspose.slides/shapetype/NOT_DEFINED) را برمی‌گرداند. |
| [`x`](/slides/python-net/fa/aspose.slides.charts/idatalabel/x/) |  |
| [`y`](/slides/python-net/fa/aspose.slides.charts/idatalabel/y/) |  |
| [`width`](/slides/python-net/fa/aspose.slides.charts/idatalabel/width/) |  |
| [`height`](/slides/python-net/fa/aspose.slides.charts/idatalabel/height/) |  |
| [`right`](/slides/python-net/fa/aspose.slides.charts/idatalabel/right/) |  |
| [`bottom`](/slides/python-net/fa/aspose.slides.charts/idatalabel/bottom/) |  |
| [`chart`](/slides/python-net/fa/aspose.slides.charts/idatalabel/chart/) |  |
| [`slide`](/slides/python-net/fa/aspose.slides.charts/idatalabel/slide/) |  |
| [`presentation`](/slides/python-net/fa/aspose.slides.charts/idatalabel/presentation/) |  |
| [`text_frame_for_overriding`](/slides/python-net/fa/aspose.slides.charts/idatalabel/text_frame_for_overriding/) |  |
| [`text_format`](/slides/python-net/fa/aspose.slides.charts/idatalabel/text_format/) |  |
| [`actual_x`](/slides/python-net/fa/aspose.slides.charts/idatalabel/actual_x/) |  |
| [`actual_y`](/slides/python-net/fa/aspose.slides.charts/idatalabel/actual_y/) |  |
| [`actual_width`](/slides/python-net/fa/aspose.slides.charts/idatalabel/actual_width/) |  |
| [`actual_height`](/slides/python-net/fa/aspose.slides.charts/idatalabel/actual_height/) |  |

## متدها

| Method | Description |
| :- | :- |
| [`hide(self)`](/slides/python-net/fa/aspose.slides.charts/idatalabel/hide/#) | برچسب داده را با تنظیم تمام پرچم‌های Show*-flags (ShowValue, ...) به حالت false مخفی می‌کند.<br/>            پس از این IsVisible برابر با false خواهد بود. |
| [`get_actual_label_text(self)`](/slides/python-net/fa/aspose.slides.charts/idatalabel/get_actual_label_text/#) | متن واقعی برچسب را بر اساس تنظیمات DataLabelFormat یا مقدار TextFrameForOverriding.Text برمی‌گرداند. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/fa/aspose.slides.charts/idatalabel/add_text_frame_for_overriding/#str) |  |

### موارد مرتبط
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)