---
title: IHtmlGenerator class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.export/ihtmlgenerator/
---
## IHtmlGenerator کلاس

Html generator.

The IHtmlGenerator type exposes the following members:

## خصوصیات

| ویژگی | توضیح |
| :- | :- |
| [`slide_image_size`](/slides/python-net/fa/aspose.slides.export/ihtmlgenerator/slide_image_size/) | اندازه تصویر اسلاید را برمی‌گرداند.<br/>            فقط‌خواندنی **aspose.slides.SizeF**. |
| [`slide_image_size_unit`](/slides/python-net/fa/aspose.slides.export/ihtmlgenerator/slide_image_size_unit/) | یک واحد که در آن اندازه تصویر اسلاید مشخص می‌شود را برمی‌گرداند.<br/>            فقط‌خواندنی [`SvgCoordinateUnit`](/slides/python-net/fa/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/fa/aspose.slides.export/ihtmlgenerator/slide_image_size_unit_code/) | کد CSS واحدی که در آن اندازه تصویر اسلاید مشخص می‌شود را برمی‌گرداند.<br/>            فقط‌خواندنی **str**. |
| [`previous_slide_index`](/slides/python-net/fa/aspose.slides.export/ihtmlgenerator/previous_slide_index/) | ایندکس اسلاید قبلاً رندر شده یا -1 اگر اولین اسلاید در حال رندر باشد را برمی‌گرداند.<br/>            فقط‌خواندنی **int**. |
| [`slide_index`](/slides/python-net/fa/aspose.slides.export/ihtmlgenerator/slide_index/) | ایندکس اسلاید در حال رندر شدن را برمی‌گرداند.<br/>            فقط‌خواندنی **int**. |
| [`next_slide_index`](/slides/python-net/fa/aspose.slides.export/ihtmlgenerator/next_slide_index/) | ایندکس اسلایدی که بعد از اسلاید فعلی رندر خواهد شد یا -1 اگر اسلاید جاری آخرین اسلاید باشد را برمی‌گرداند.<br/>            فقط‌خواندنی **int**. |

## متدها

| متد | توضیح |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/fa/aspose.slides.export/ihtmlgenerator/add_html/#str) | متن HTML قالب‌بندی‌شده را اضافه می‌کند. |
| [`add_html(self, html)`](/slides/python-net/fa/aspose.slides.export/ihtmlgenerator/add_html/#listchar) | متن HTML قالب‌بندی‌شده را اضافه می‌کند. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/fa/aspose.slides.export/ihtmlgenerator/add_html/#listchar-int-int) | متن HTML قالب‌بندی‌شده را اضافه می‌کند. |
| [`add_text(self, text)`](/slides/python-net/fa/aspose.slides.export/ihtmlgenerator/add_text/#str) | متن ساده را به فایل‌های html اضافه می‌کند و کاراکترهای ویژه را به موجودیت‌های html تبدیل می‌کند.<br/>            شکست‌های خط و فضاهای سفید جایگزین نمی‌شوند. |
| [`add_text(self, text)`](/slides/python-net/fa/aspose.slides.export/ihtmlgenerator/add_text/#listchar) | متن ساده را به فایل‌های html اضافه می‌کند و کاراکترهای ویژه را به موجودیت‌های html تبدیل می‌کند.<br/>            شکست‌های خط و فضاهای سفید جایگزین نمی‌شوند. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/fa/aspose.slides.export/ihtmlgenerator/add_text/#listchar-int-int) | متن ساده را به فایل‌های html اضافه می‌کند و کاراکترهای ویژه را به موجودیت‌های html تبدیل می‌کند.<br/>            شکست‌های خط و فضاهای سفید جایگزین نمی‌شوند. |
| [`add_attribute_value(self, value)`](/slides/python-net/fa/aspose.slides.export/ihtmlgenerator/add_attribute_value/#str) | مقدار ویژگی را کوتیشن می‌زند و به فایل html اضافه می‌کند. |
| [`add_attribute_value(self, value)`](/slides/python-net/fa/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar) | مقدار ویژگی را کوتیشن می‌زند و به فایل html اضافه می‌کند. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/fa/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar-int-int) | مقدار ویژگی را کوتیشن می‌زند و به فایل html اضافه می‌کند. |

### موارد مرتبط
* ماژول [`aspose.slides.export`](/slides/python-net/fa/aspose.slides.export)
* کتابخانه [`Aspose.Slides`](/slides/python-net)