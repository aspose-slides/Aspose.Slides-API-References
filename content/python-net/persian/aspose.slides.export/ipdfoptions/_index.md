---
title: IPdfOptions class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.export/ipdfoptions/
---
## IPdfOptions کلاس

گزینه‌هایی را فراهم می‌کند که نحوهٔ ذخیره‌سازی یک ارائه در قالب Pdf را کنترل می‌کند.

نوع IPdfOptions اعضای زیر را ارائه می‌دهد:

## ویژگی‌ها

| خاصیت | توضیح |
| :- | :- |
| [`text_compression`](/slides/python-net/fa/aspose.slides.export/ipdfoptions/text_compression/) | نوع فشرده‌سازی را که برای تمام محتوای متنی در سند استفاده می‌شود، مشخص می‌کند.<br/>            خواندن/نوشتن [`PdfTextCompression`](/slides/python-net/fa/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/fa/aspose.slides.export/ipdfoptions/best_images_compression_ratio/) | نشان می‌دهد که آیا فشرده‌سازی مؤثرترین (به جای پیش‌فرض) برای هر تصویر باید به طور خودکار انتخاب شود<br/>            اگر به **bool**.true تنظیم شود، برای هر تصویر در ارائه، مناسب‌ترین الگوریتم فشرده‌سازی انتخاب می‌شود که منجر به اندازهٔ کوچکتر سند PDF حاصل می‌گردد.<br/>            انتخاب بهترین نسبت فشرده‌سازی تصویر هزینه محاسباتی بالایی دارد و مقدار RAM اضافی مصرف می‌کند، و این گزینه به طور پیش‌فرض **bool**.false است. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/fa/aspose.slides.export/ipdfoptions/embed_true_type_fonts_for_ascii/) | برای جاسازی قلم‌های TrueType برای کاراکترهای ASCII 32-127 مقدار True تنظیم شود.<br/>            قلم‌ها برای کدهای کاراکتری بزرگتر از 127 همیشه جاسازی می‌شوند.<br/>            خواندن/نوشتن **bool**. |
| [`show_hidden_slides`](/slides/python-net/fa/aspose.slides.export/ipdfoptions/show_hidden_slides/) | مشخص می‌کند که آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه.<br/>            مقدار پیش‌فرض `false` است. |
| [`additional_common_font_families`](/slides/python-net/fa/aspose.slides.export/ipdfoptions/additional_common_font_families/) | یک آرایه از نام‌های تعریف‌شده توسط کاربر برای خانواده‌های قلم که Aspose.Slides باید آنها را مشترک در نظر بگیرد، بازمی‌گرداند یا تنظیم می‌کند.<br/>            خواندن/نوشتن **str**[]. |
| [`embed_full_fonts`](/slides/python-net/fa/aspose.slides.export/ipdfoptions/embed_full_fonts/) | تعیین می‌کند که آیا تمام کاراکترهای قلم باید جاسازی شوند یا فقط زیرمجموعهٔ استفاده‌شده.<br/>            خواندن/نوشتن **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/fa/aspose.slides.export/ipdfoptions/rasterize_unsupported_font_styles/) | نشان می‌دهد که آیا متن باید به صورت bitmap رستر شود و در PDF ذخیره شود وقتی قلم از استایل bold پشتیبانی نمی‌کند.<br/>            این روش می‌تواند کیفیت متن در PDF حاصل را برای برخی قلم‌ها بهبود بخشد.<br/>            خواندن/نوشتن **bool**. |
| [`jpeg_quality`](/slides/python-net/fa/aspose.slides.export/ipdfoptions/jpeg_quality/) | مقداری را که کیفیت تصاویر JPEG داخل سند PDF را تعیین می‌کند، بازمی‌گرداند یا تنظیم می‌کند.<br/>            خواندن/نوشتن **int**. |
| [`compliance`](/slides/python-net/fa/aspose.slides.export/ipdfoptions/compliance/) | سطح انطباق مطلوب برای سند PDF تولید شده.<br/>            خواندن/نوشتن [`PdfCompliance`](/slides/python-net/fa/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/fa/aspose.slides.export/ipdfoptions/password/) | تنظیم گذرواژهٔ کاربر برای حفاظت از سند PDF.<br/>            خواندن/نوشتن **str**. |
| [`access_permissions`](/slides/python-net/fa/aspose.slides.export/ipdfoptions/access_permissions/) | مجموعه‌ای از پرچم‌ها را شامل می‌شود که مشخص می‌کند هنگام باز کردن سند با دسترسی کاربر کدام مجوزهای دسترسی اعطاشده باشند.<br/>            ببینید [`PdfAccessPermissions`](/slides/python-net/fa/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/fa/aspose.slides.export/ipdfoptions/save_metafiles_as_png/) | برای تبدیل تمام متافایل‌های استفاده‌شده در یک ارائه به تصاویر PNG مقدار True تنظیم شود.<br/>            خواندن/نوشتن **bool**. |
| [`sufficient_resolution`](/slides/python-net/fa/aspose.slides.export/ipdfoptions/sufficient_resolution/) | مقداری را که وضوح تصاویر داخل سند PDF را تعیین می‌کند، بازمی‌گرداند یا تنظیم می‌کند.<br/>            <br/>این خاصیت بر اندازهٔ فایل، زمان خروجی‌گیری و کیفیت تصویر تأثیر می‌گذارد.<br/><br/><br/>مقدار پیش‌فرض **96** است.<br/><br/><br/>            خواندن/نوشتن **float**. |
| [`draw_slides_frame`](/slides/python-net/fa/aspose.slides.export/ipdfoptions/draw_slides_frame/) | برای رسم قاب سیاه دور هر اسلاید مقدار True تنظیم شود.<br/>            خواندن/نوشتن **bool**. |
| [`slides_layout_options`](/slides/python-net/fa/aspose.slides.export/ipdfoptions/slides_layout_options/) | حالت قرارگیری اسلایدها روی صفحه هنگام خروجی‌گیری یک ارائه را دریافت یا تنظیم می‌کند [`ISlidesLayoutOptions`](/slides/python-net/fa/aspose.slides.export/islideslayoutoptions). |
| [`image_transparent_color`](/slides/python-net/fa/aspose.slides.export/ipdfoptions/image_transparent_color/) | رنگ شفاف تصویر را دریافت یا تنظیم می‌کند. |
| [`apply_image_transparent`](/slides/python-net/fa/aspose.slides.export/ipdfoptions/apply_image_transparent/) | اگر `true` باشد، رنگ شفاف مشخص‌شده را بر تصویری اعمال می‌کند. |
| [`ink_options`](/slides/python-net/fa/aspose.slides.export/ipdfoptions/ink_options/) | گزینه‌هایی را فراهم می‌کند که ظاهر اشیای Ink را در سند خروجی‌شده کنترل می‌کند.<br/>            فقط‌خواندنی [`IInkOptions`](/slides/python-net/fa/aspose.slides.export/iinkoptions) |
| [`include_ole_data`](/slides/python-net/fa/aspose.slides.export/ipdfoptions/include_ole_data/) | برای تبدیل تمام داده‌های OLE از ارائه به فایل‌های جاسازی‌شده در PDF حاصل مقدار True تنظیم شود.<br/>            خواندن/نوشتن **bool**. |
| [`warning_callback`](/slides/python-net/fa/aspose.slides.export/ipdfoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/fa/aspose.slides.export/ipdfoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/fa/aspose.slides.export/ipdfoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/fa/aspose.slides.export/ipdfoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/fa/aspose.slides.export/ipdfoptions/skip_java_script_links/) |  |

### مراجع
* ماژول [`aspose.slides.export`](/slides/python-net/fa/aspose.slides.export)
* کتابخانه [`Aspose.Slides`](/slides/python-net)