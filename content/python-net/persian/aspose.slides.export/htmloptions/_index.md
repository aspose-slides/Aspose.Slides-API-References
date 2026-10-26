---
title: HtmlOptions class
second_title: Aspose.Slides برای Python از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides.export/htmloptions/
---
## HtmlOptions کلاس

نمایانگر گزینه‌های خروجی HTML است.

**ارث‌بری:**[`HtmlOptions`](/slides/python-net/fa/aspose.slides.export/htmloptions) → [`SaveOptions`](/slides/python-net/fa/aspose.slides.export/saveoptions)

نوع HtmlOptions اعضای زیر را در اختیار می‌گذارد:

## سازنده‌ها

| سازنده | توضیح |
| :- | :- |
| [`__init__(self, link_embed_controller)`](/slides/python-net/fa/aspose.slides.export/htmloptions/__init__/#ilinkembedcontroller) | یک شیء جدید HtmlOptions را با مشخص کردن callback ایجاد می‌کند. |
| [`__init__(self)`](/slides/python-net/fa/aspose.slides.export/htmloptions/__init__/#) | یک شیء جدید HtmlOptions را برای ذخیره در یک فایل HTML تک‌فایل ایجاد می‌کند. |

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`warning_callback`](/slides/python-net/fa/aspose.slides.export/htmloptions/warning_callback/) | یک شیء را برمی‌گرداند یا تنظیم می‌کند که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا لغو شود.<br/>            خواندن/نوشتن [`IWarningCallback`](/slides/python-net/fa/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/fa/aspose.slides.export/htmloptions/progress_callback/) | یک شئ callback را نشان می‌دهد برای به‌روزرسانی پیشرفت ذخیره‌سازی به درصد.<br/>            نگاه کنید به [`IProgressCallback`](/slides/python-net/fa/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/fa/aspose.slides.export/htmloptions/default_regular_font/) | یک فونت را برمی‌گرداند یا تنظیم می‌کند که در صورت یافت نشدن فونت منبع استفاده می‌شود.<br/>            خواندن/نوشتن **str**. |
| [`gradient_style`](/slides/python-net/fa/aspose.slides.export/htmloptions/gradient_style/) | سبک بصری گرادیان را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندن/نوشتن [`GradientStyle`](/slides/python-net/fa/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/fa/aspose.slides.export/htmloptions/skip_java_script_links/) | مشخص می‌کند که آیا هنگام ذخیره ارائه، پیوندهای فراخوانی JavaScript را رد کند یا نه.<br/>            خواندن/نوشتن **bool**. مقدار پیش‌فرض **false** است. |
| [`slides_layout_options`](/slides/python-net/fa/aspose.slides.export/htmloptions/slides_layout_options/) | حالت قرارگیری اسلایدها بر صفحه هنگام خروجی گرفتن ارائه را بر می‌گیرد یا تنظیم می‌کند [`ISlidesLayoutOptions`](/slides/python-net/fa/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/fa/aspose.slides.export/htmloptions/ink_options/) | گزینه‌هایی را فراهم می‌کند که ظاهر اشیاء Ink را در سند خروجی کنترل می‌کند.<br/>            فقط-خواندنی [`IInkOptions`](/slides/python-net/fa/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/fa/aspose.slides.export/htmloptions/show_hidden_slides/) | مشخص می‌کند که سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه.<br/>            مقدار پیش‌فرض `false`. |
| [`html_formatter`](/slides/python-net/fa/aspose.slides.export/htmloptions/html_formatter/) | قالب HTML را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندن/نوشتن [`IHtmlFormatter`](/slides/python-net/fa/aspose.slides.export/ihtmlformatter). |
| [`disable_font_ligatures`](/slides/python-net/fa/aspose.slides.export/htmloptions/disable_font_ligatures/) | مقدار را بر می‌گیرد یا تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لگیچرها رندر شود یا نه.<br/>            وقتی به `true` تنظیم شود، لگیچرها در خروجی رندر شده غیرفعال خواهند شد. به طور پیش‌فرض، این ویژگی به `false` تنظیم شده است. |
| [`slide_image_format`](/slides/python-net/fa/aspose.slides.export/htmloptions/slide_image_format/) | گزینه‌های قالب تصویر اسلاید را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندن/نوشتن [`ISlideImageFormat`](/slides/python-net/fa/aspose.slides.export/islideimageformat). |
| [`jpeg_quality`](/slides/python-net/fa/aspose.slides.export/htmloptions/jpeg_quality/) | مقدار را برمی‌گرداند یا تنظیم می‌کند که کیفیت تصاویر JPEG داخل سند PDF را تعیین می‌کند.<br/>            خواندن/نوشتن **int**. |
| [`pictures_compression`](/slides/python-net/fa/aspose.slides.export/htmloptions/pictures_compression/) | سطح فشرده‌سازی تصاویر را نشان می‌دهد |
| [`delete_pictures_cropped_areas`](/slides/python-net/fa/aspose.slides.export/htmloptions/delete_pictures_cropped_areas/) | یک پرچم بولی نشان می‌دهد آیا قسمت‌های برش خورده به عنوان بخشی از سند باقی می‌مانند یا نه. اگر true قسمت‌های برش خورده حذف خواهند شد، اگر false در سند سریال‌سازی می‌شوند (که ممکن است منجر به فایل بزرگتر شود) |
| [`svg_responsive_layout`](/slides/python-net/fa/aspose.slides.export/htmloptions/svg_responsive_layout/) | اگر true، ویژگی‌های width و height را از محفظه svg حذف می‌کند - این باعث می‌شود طرح‌بندی واکنش‌گرا باشد. اگر false، خلاف آن.<br/>            خواندن/نوشتن **bool**. |

### موارد مرتبط
* کلاس [`HtmlOptions`](/slides/python-net/fa/aspose.slides.export/htmloptions)
* کلاس [`SaveOptions`](/slides/python-net/fa/aspose.slides.export/saveoptions)
* ماژول [`aspose.slides.export`](/slides/python-net/fa/aspose.slides.export)
* کتابخانه [`Aspose.Slides`](/slides/python-net)