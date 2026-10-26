---
title: PdfOptions class
second_title: Aspose.Slides برای Python از طریق مرجع API .NET
description: 
type: docs
url: /fa/aspose.slides.export/pdfoptions/
---
## PdfOptions کلاس

گزینه‌هایی را فراهم می‌کند که نحوهٔ ذخیرهٔ یک ارائه در قالب Pdf را کنترل می‌کند.

**ارث‌بری:**[`PdfOptions`](/slides/python-net/fa/aspose.slides.export/pdfoptions) → [`SaveOptions`](/slides/python-net/fa/aspose.slides.export/saveoptions)

نوع PdfOptions اعضای زیر را در اختیار می‌گذارد:

## سازنده‌ها

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fa/aspose.slides.export/pdfoptions/__init__/#) | سازندهٔ پیش‌فرض. |

## ویژگی‌ها

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/fa/aspose.slides.export/pdfoptions/warning_callback/) | یک شیء را که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود، باز می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی [`IWarningCallback`](/slides/python-net/fa/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/fa/aspose.slides.export/pdfoptions/progress_callback/) | یک شیء callback را برای به‌روزرسانی‌های پیشرفت ذخیره‌سازی به درصد نشان می‌دهد.<br/>            ببینید [`IProgressCallback`](/slides/python-net/fa/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/fa/aspose.slides.export/pdfoptions/default_regular_font/) | فونتی را که در صورت عدم یافتن فونت منبع استفاده می‌شود، باز می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **str**. |
| [`gradient_style`](/slides/python-net/fa/aspose.slides.export/pdfoptions/gradient_style/) | سبک بصری گرادیان را باز می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی [`GradientStyle`](/slides/python-net/fa/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/fa/aspose.slides.export/pdfoptions/skip_java_script_links/) | مشخص می‌کند که آیا هنگام ذخیرهٔ ارائه، پیوندهای حاوی فراخوانی‌های JavaScript نادیده گرفته شوند یا نه.<br/>            خواندنی/نوشتنی **bool**. مقدار پیش‌فرض **false** است. |
| [`slides_layout_options`](/slides/python-net/fa/aspose.slides.export/pdfoptions/slides_layout_options/) | حالت قرارگیری اسلایدها بر روی صفحه هنگام خروجی گرفتن از یک ارائه را باز می‌گرداند یا تنظیم می‌کند [`ISlidesLayoutOptions`](/slides/python-net/fa/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/fa/aspose.slides.export/pdfoptions/ink_options/) | گزینه‌هایی را فراهم می‌کند که ظاهر اشیای Ink در سند خروجی را کنترل می‌کند.<br/>            فقط‌خواندنی [`IInkOptions`](/slides/python-net/fa/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/fa/aspose.slides.export/pdfoptions/show_hidden_slides/) | مشخص می‌کند که آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا خیر.<br/>            مقدار پیش‌فرض `false` است. |
| [`text_compression`](/slides/python-net/fa/aspose.slides.export/pdfoptions/text_compression/) | نوع فشرده‌سازی مورد استفاده برای تمام محتوای متنی در سند را مشخص می‌کند.<br/>            خواندنی/نوشتنی [`PdfTextCompression`](/slides/python-net/fa/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/fa/aspose.slides.export/pdfoptions/best_images_compression_ratio/) | مشخص می‌کند آیا فشرده‌سازی مؤثرترین (به جای پیش‌فرض) برای هر تصویر به‌صورت خودکار انتخاب شود<br/>            اگر به **bool**.true تنظیم شود، برای هر تصویر در ارائه، بهینه‌ترین الگوریتم فشرده‌سازی انتخاب می‌شود که منجر به کوچک‌تر شدن حجم سند PDF خروجی می‌شود.<br/>            انتخاب بهترین نسبت فشرده‌سازی تصویر هزینهٔ محاسباتی بالایی دارد و حافظهٔ RAM بیشتری مصرف می‌کند، و این گزینه به طور پیش‌فرض **bool**.false است. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/fa/aspose.slides.export/pdfoptions/embed_true_type_fonts_for_ascii/) | مشخص می‌کند آیا Aspose.Slides فونت‌های عمومی را برای متن ASCII (بازه کد 33..127) جاسازی می‌کند یا خیر.<br/>            فونت‌ها برای کدهای کاراکتر بیش از 127 همیشه جاسازی می‌شوند.<br/>            فهرست فونت‌های عمومی شامل 14 فونت پایه PDF و فونت‌های اضافه‌شده توسط کاربر است.<br/>            خواندنی/نوشتنی **bool**. |
| [`additional_common_font_families`](/slides/python-net/fa/aspose.slides.export/pdfoptions/additional_common_font_families/) | یک آرایه از نام‌های تعریف‌شده توسط کاربر برای خانواده‌های فونت که Aspose.Slides باید به‌عنوان عمومی در نظر بگیرد، باز می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **str**[]. |
| [`embed_full_fonts`](/slides/python-net/fa/aspose.slides.export/pdfoptions/embed_full_fonts/) | مشخص می‌کند آیا تمام کاراکترهای فونت باید جاسازی شوند یا فقط زیرمجموعهٔ استفاده‌شده.<br/>            خواندنی/نوشتنی **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/fa/aspose.slides.export/pdfoptions/rasterize_unsupported_font_styles/) | مشخص می‌کند آیا متن باید به صورت bitmap رستر شود و به PDF ذخیره شود هنگامی که فونت از استایل بولد پشتیبانی نمی‌کند.<br/>            این روش می‌تواند کیفیت متن در PDF حاصل برای برخی فونت‌ها را بهبود بخشد.<br/>            خواندنی/نوشتنی **bool**. |
| [`jpeg_quality`](/slides/python-net/fa/aspose.slides.export/pdfoptions/jpeg_quality/) | مقداری که کیفیت تصاویر JPEG داخل سند PDF را تعیین می‌کند، باز می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **int**. |
| [`compliance`](/slides/python-net/fa/aspose.slides.export/pdfoptions/compliance/) | سطح انطباق مطلوب برای سند PDF تولید شده.<br/>            خواندنی/نوشتنی [`PdfCompliance`](/slides/python-net/fa/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/fa/aspose.slides.export/pdfoptions/password/) | تنظیم رمز عبور کاربر برای محافظت از سند PDF.<br/>            خواندنی/نوشتنی **str**. |
| [`access_permissions`](/slides/python-net/fa/aspose.slides.export/pdfoptions/access_permissions/) | مجموعه‌ای از پرچم‌ها را شامل می‌شود که مشخص می‌کند چه دسترسی‌هایی هنگام باز شدن سند با دسترسی کاربر ارائه شود.<br/>            ببینید [`PdfAccessPermissions`](/slides/python-net/fa/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/fa/aspose.slides.export/pdfoptions/save_metafiles_as_png/) | اگر true باشد، تمام متافایل‌های استفاده‌شده در یک ارائه به تصاویر PNG تبدیل می‌شوند.<br/>            خواندنی/نوشتنی **bool**. |
| [`sufficient_resolution`](/slides/python-net/fa/aspose.slides.export/pdfoptions/sufficient_resolution/) | مقداری که وضوح تصاویر داخل سند PDF را تعیین می‌کند، باز می‌گرداند یا تنظیم می‌کند.<br/>            <br/>این ویژگی بر حجم فایل، زمان خروجی‌گیری و کیفیت تصویر تأثیر دارد.<br/><br/><br/>مقدار پیش‌فرض **96** است.<br/><br/><br/>            خواندنی/نوشتنی **float**. |
| [`draw_slides_frame`](/slides/python-net/fa/aspose.slides.export/pdfoptions/draw_slides_frame/) | اگر true باشد، برای هر اسلاید یک چارچوب سیاه رسم می‌شود.<br/>            خواندنی/نوشتنی **bool**. |
| [`image_transparent_color`](/slides/python-net/fa/aspose.slides.export/pdfoptions/image_transparent_color/) | رنگ شفاف تصویر را باز می‌گرداند یا تنظیم می‌کند. |
| [`apply_image_transparent`](/slides/python-net/fa/aspose.slides.export/pdfoptions/apply_image_transparent/) | اگر `true` باشد، رنگ شفاف مشخص‌شده را به تصویر اعمال می‌کند. |
| [`include_ole_data`](/slides/python-net/fa/aspose.slides.export/pdfoptions/include_ole_data/) | اگر true باشد، تمام داده‌های OLE از ارائه به فایل‌های جاسازی‌شده در PDF خروجی تبدیل می‌شوند.<br/>            خواندنی/نوشتنی **bool**. |

### موارد مرتبط
* کلاس [`PdfOptions`](/slides/python-net/fa/aspose.slides.export/pdfoptions)
* کلاس [`SaveOptions`](/slides/python-net/fa/aspose.slides.export/saveoptions)
* ماژول [`aspose.slides.export`](/slides/python-net/fa/aspose.slides.export)
* کتابخانه [`Aspose.Slides`](/slides/python-net)