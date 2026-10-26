---
title: IHtmlGenerator class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.export/ihtmlgenerator/
---
## IHtmlGenerator کلاس

مولد HTML.

نوع IHtmlGenerator اعضای زیر را نمایش می‌دهد:

## خصوصیات

| ویژگی | توضیح |
| :- | :- |
| [`slide_image_size`](/slides/python-net/fa/aspose.slides.export/ihtmlgenerator/slide_image_size/) | اندازۀ تصویر اسلاید را برمی‌گرداند.<br/>            فقط-خواندنی [`SizeF`](/slides/python-net/fa/aspose.slides/sizef). |
| [`slide_image_size_unit`](/slides/python-net/fa/aspose.slides.export/ihtmlgenerator/slide_image_size_unit/) | واحدی که اندازه تصویر اسلاید در آن مشخص می‌شود را برمی‌گرداند.<br/>            فقط-خواندنی [`SvgCoordinateUnit`](/slides/python-net/fa/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/fa/aspose.slides.export/ihtmlgenerator/slide_image_size_unit_code/) | کد CSS واحدی که اندازه تصویر اسلاید در آن مشخص می‌شود را برمی‌گرداند.<br/>            فقط-خواندنی **str**. |
| [`previous_slide_index`](/slides/python-net/fa/aspose.slides.export/ihtmlgenerator/previous_slide_index/) | اندیس اسلاید قبلاً رندر شده یا -1 اگر اولین اسلاید در حال رندر باشد را برمی‌گرداند.<br/>            فقط-خواندنی **int**. |
| [`slide_index`](/slides/python-net/fa/aspose.slides.export/ihtmlgenerator/slide_index/) | اندیس اسلاید در حال رندر شدن را برمی‌گرداند.<br/>            فقط-خواندنی **int**. |
| [`next_slide_index`](/slides/python-net/fa/aspose.slides.export/ihtmlgenerator/next_slide_index/) | اندیس اسلایدی که پس از اسلاید فعلی رندر می‌شود یا -1 اگر در حال رندر اسلاید آخر باشد را برمی‌گرداند.<br/>            فقط-خواندنی **int**. |

## متدها

| متد | توضیح |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/fa/aspose.slides.export/ihtmlgenerator/add_html/#str) | متن HTML قالب‌بندی‌شده را اضافه می‌کند. |
| [`add_html(self, html)`](/slides/python-net/fa/aspose.slides.export/ihtmlgenerator/add_html/#listchar) | متن HTML قالب‌بندی‌شده را اضافه می‌کند. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/fa/aspose.slides.export/ihtmlgenerator/add_html/#listchar-int-int) | متن HTML قالب‌بندی‌شده را اضافه می‌کند. |
| [`add_text(self, text)`](/slides/python-net/fa/aspose.slides.export/ihtmlgenerator/add_text/#str) | متن ساده را به فایل‌های html اضافه می‌کند، کاراکترهای خاص را با موجودیت‌های html جایگزین می‌کند.<br/>            خطوط شکسته و فضای خالی جایگزین نمی‌شوند. |
| [`add_text(self, text)`](/slides/python-net/fa/aspose.slides.export/ihtmlgenerator/add_text/#listchar) | متن ساده را به فایل‌های html اضافه می‌کند، کاراکترهای خاص را با موجودیت‌های html جایگزین می‌کند.<br/>            خطوط شکسته و فضای خالی جایگزین نمی‌شوند. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/fa/aspose.slides.export/ihtmlgenerator/add_text/#listchar-int-int) | متن ساده را به فایل‌های html اضافه می‌کند، کاراکترهای خاص را با موجودیت‌های html جایگزین می‌کند.<br/>            خطوط شکسته و فضای خالی جایگزین نمی‌شوند. |
| [`add_attribute_value(self, value)`](/slides/python-net/fa/aspose.slides.export/ihtmlgenerator/add_attribute_value/#str) | مقدار ویژگی را نقل قول می‌کند و به فایل html اضافه می‌کند. |
| [`add_attribute_value(self, value)`](/slides/python-net/fa/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar) | مقدار ویژگی را نقل قول می‌کند و به فایل html اضافه می‌کند. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/fa/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar-int-int) | مقدار ویژگی را نقل قول می‌کند و به فایل html اضافه می‌کند. |

### مراجع
* ماژول [`aspose.slides.export`](/slides/python-net/fa/aspose.slides.export)
* کتابخانه [`Aspose.Slides`](/slides/python-net)