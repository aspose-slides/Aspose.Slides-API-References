---
title: MarkdownSaveOptions class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions کلاس

گزینه‌هایی را توصیف می‌کند که کنترل می‌کند ارائه چگونه باید به markdown ذخیره شود.

**ارث‌بری:**[`MarkdownSaveOptions`](/slides/python-net/fa/aspose.slides.export/markdownsaveoptions) → [`SaveOptions`](/slides/python-net/fa/aspose.slides.export/saveoptions)

نوع MarkdownSaveOptions اعضای زیر را در اختیار می‌گذارد:

## سازنده‌ها

| سازنده | توضیح |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fa/aspose.slides.export/markdownsaveoptions/__init__/#) | Ctor. |

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`warning_callback`](/slides/python-net/fa/aspose.slides.export/markdownsaveoptions/warning_callback/) | یک شیء که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا لغو شود، باز می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی [`IWarningCallback`](/slides/python-net/fa/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/fa/aspose.slides.export/markdownsaveoptions/progress_callback/) | یک شیء callback برای به‌روزرسانی پیشرفت ذخیره‌سازی بر حسب درصد را نشان می‌دهد.<br/>            ببینید [`IProgressCallback`](/slides/python-net/fa/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/fa/aspose.slides.export/markdownsaveoptions/default_regular_font/) | در صورتی که فونت منبع یافت نشود، فونت استفاده شده را بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی-نوشتنی **str**. |
| [`gradient_style`](/slides/python-net/fa/aspose.slides.export/markdownsaveoptions/gradient_style/) | سبک بصری گرادیان را بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی [`GradientStyle`](/slides/python-net/fa/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/fa/aspose.slides.export/markdownsaveoptions/skip_java_script_links/) | مشخص می‌کند که آیا هنگام ذخیره‌سازی ارائه، پیوندهای حاوی فراخوانی‌های JavaScript نادیده گرفته شوند یا نه.<br/>            خواندنی/نوشتنی **bool**. مقدار پیش‌فرض **false** است. |
| [`export_type`](/slides/python-net/fa/aspose.slides.export/markdownsaveoptions/export_type/) | مشخص می‌کند که از کدام مشخصات markdown برای تبدیل ارائه استفاده شود.<br/>            پیش‌فرض `TextOnly` است. |
| [`base_path`](/slides/python-net/fa/aspose.slides.export/markdownsaveoptions/base_path/) | مسیر پایه‌ای را که سند با منابع در آن ذخیره می‌شود مشخص می‌کند.<br/>            پیش‌فرض دایرکتوری جاری برنامه است. |
| [`images_save_folder_name`](/slides/python-net/fa/aspose.slides.export/markdownsaveoptions/images_save_folder_name/) | نام پوشه‌ای را برای ذخیره تصاویر مشخص می‌کند.<br/>            پیش‌فرض `Images` است. |
| [`new_line_type`](/slides/python-net/fa/aspose.slides.export/markdownsaveoptions/new_line_type/) | مشخص می‌کند سند تولید شده باید از خطوط جدید \\r(Macintosh) یا \\n(Unix) یا \\r\\n(Windows) استفاده کند.<br/>            پیش‌فرض `Unix` است. |
| [`show_comments`](/slides/python-net/fa/aspose.slides.export/markdownsaveoptions/show_comments/) | مشخص می‌کند سند تولید شده نظرات را نشان دهد یا نه.<br/>            پیش‌فرض `false` است. |
| [`show_hidden_slides`](/slides/python-net/fa/aspose.slides.export/markdownsaveoptions/show_hidden_slides/) | مشخص می‌کند سند تولید شده اسلایدهای مخفی را شامل شود یا نه.<br/>            پیش‌فرض `false` است. |
| [`show_slide_number`](/slides/python-net/fa/aspose.slides.export/markdownsaveoptions/show_slide_number/) | مشخص می‌کند سند تولید شده شماره هر اسلاید را نشان دهد یا نه.<br/>            پیش‌فرض `false` است. |
| [`flavor`](/slides/python-net/fa/aspose.slides.export/markdownsaveoptions/flavor/) | مشخص می‌کند که از کدام مشخصات markdown برای تبدیل ارائه استفاده شود.<br/>            پیش‌فرض `Multi-markdown` است. |
| [`slide_number_format`](/slides/python-net/fa/aspose.slides.export/markdownsaveoptions/slide_number_format/) | رشته قالبی را که برای سرصفحه شماره اسلاید در خروجی Markdown استفاده می‌شود، بر می‌گرداند یا تنظیم می‌کند.<br/>            قالب باید مکان‌دار \"{0}\" را شامل باشد که هنگام صادر کردن با شمارهٔ اسلاید جایگزین می‌شود.<br/>            مثال: \"# Slide {0}\" منجر به تولید \"# Slide 1\"، \"# Slide 2\" و غیره می‌شود. |
| [`handle_repeated_spaces`](/slides/python-net/fa/aspose.slides.export/markdownsaveoptions/handle_repeated_spaces/) |  |
| [`remove_empty_lines`](/slides/python-net/fa/aspose.slides.export/markdownsaveoptions/remove_empty_lines/) | اگر بر روی `true` تنظیم شود، خطوط خالی یا فقط حاوی فاصله را از خروجی نهایی Markdown حذف می‌کند.<br/>            پیش‌فرض `false` است. |

### موارد مرتبط
* کلاس [`MarkdownSaveOptions`](/slides/python-net/fa/aspose.slides.export/markdownsaveoptions)
* کلاس [`SaveOptions`](/slides/python-net/fa/aspose.slides.export/saveoptions)
* ماژول [`aspose.slides.export`](/slides/python-net/fa/aspose.slides.export)
* کتابخانه [`Aspose.Slides`](/slides/python-net)