---
title: ISVGOptions class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.export/isvgoptions/
---
## ISVGOptions کلاس

نمایانگر گزینه‌های SVG است.

نوع ISVGOptions اعضای زیر را ارائه می‌دهد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`vectorize_text`](/slides/python-net/fa/aspose.slides.export/isvgoptions/vectorize_text/) | مشخص می‌کند که آیا متن روی اسلاید به صورت گرافیک ذخیره شود یا نه.<br/> خواندن/نوشتن **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/fa/aspose.slides.export/isvgoptions/metafile_rasterization_dpi/) | محدودیت وضوح پایین‌تر برای rasterization متافایل را برمی‌گرداند یا تنظیم می‌کند.<br/> خواندن/نوشتن **int**. |
| [`disable_3d_text`](/slides/python-net/fa/aspose.slides.export/isvgoptions/disable_3d_text/) | مشخص می‌کند که آیا متن ۳‌بعدی در SVG غیرفعال باشد یا نه.<br/> خواندن/نوشتن **bool**. |
| [`disable_gradient_split`](/slides/python-net/fa/aspose.slides.export/isvgoptions/disable_gradient_split/) | تقسیم گرادیان‌های FromCornerX و FromCenter را غیرفعال می‌کند.<br/> خواندن/نوشتن **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/fa/aspose.slides.export/isvgoptions/disable_line_end_cropping/) | نسخه SVG 1.1 امکان تعریف تو رفتگی برای نشانگرها را ندارد.<br/> موتور نوشتن SVG در Aspose.Slides راه‌حلی برای این مشکل دارد:<br/> انتهای خط را با پیکان برش می‌دهد، به‌طوری که خط با نشانگرها همپوشانی نکند.<br/> این گزینه این رفتار را غیرفعال می‌کند.<br/> خواندن/نوشتن **bool**. |
| [`jpeg_quality`](/slides/python-net/fa/aspose.slides.export/isvgoptions/jpeg_quality/) | کیفیت رمزگذاری JPEG را تعیین می‌کند.<br/> خواندن/نوشتن **int**. |
| [`shape_formatting_controller`](/slides/python-net/fa/aspose.slides.export/isvgoptions/shape_formatting_controller/) | یک رابط فراخوانی را برمی‌گرداند و تنظیم می‌کند که به کاربر امکان کنترل تبدیل شکل را می‌دهد.<br/> خواندن/نوشتن [`ISvgShapeFormattingController`](/slides/python-net/fa/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/fa/aspose.slides.export/isvgoptions/pictures_compression/) | سطح فشرده‌سازی تصاویر را نشان می‌دهد<br/> خواندن/نوشتن [`ISVGOptions.pictures_compression`](/slides/python-net/fa/aspose.slides.export/isvgoptions/pictures_compression). |
| [`delete_pictures_cropped_areas`](/slides/python-net/fa/aspose.slides.export/isvgoptions/delete_pictures_cropped_areas/) | یک پرچم بولی نشان می‌دهد که آیا قسمت‌های برش داده‌شده به‌عنوان بخشی از سند باقی بمانند یا نه. اگر true باشد، قسمت‌های برش داده شده حذف می‌شوند، اگر false باشند در سند سریال‌سازی می‌شوند (که می‌تواند منجر به فایل بزرگتر شود)<br/> خواندن/نوشتن **bool**. |
| [`use_frame_size`](/slides/python-net/fa/aspose.slides.export/isvgoptions/use_frame_size/) | مشخص می‌کند که آیا قاب متن در ناحیه رندرینگ گنجانده شود یا نه.<br/> خواندن/نوشتن **bool**.<br/> مقدار پیش‌فرض false است. |
| [`use_frame_rotation`](/slides/python-net/fa/aspose.slides.export/isvgoptions/use_frame_rotation/) | مشخص می‌کند که آیا در هنگام رندرینگ چرخش مشخص‌شدهٔ شکل اعمال شود یا نه.<br/> خواندن/نوشتن **bool**.<br/> مقدار پیش‌فرض true است. |
| [`external_fonts_handling`](/slides/python-net/fa/aspose.slides.export/isvgoptions/external_fonts_handling/) | روشی برای پردازش فونت‌های بارگذاری‌شده از خارج را تعیین می‌کند.<br/> خواندن/نوشتن [`SvgExternalFontsHandling`](/slides/python-net/fa/aspose.slides.export/svgexternalfontshandling). |
| [`ink_options`](/slides/python-net/fa/aspose.slides.export/isvgoptions/ink_options/) | گزینه‌هایی ارائه می‌دهد که ظاهر اشیاء Ink در سند صادرشده را کنترل می‌کند.<br/> فقط-خواندنی [`IInkOptions`](/slides/python-net/fa/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/fa/aspose.slides.export/isvgoptions/disable_font_ligatures/) | مقدار�ایی را برمی‌گرداند یا تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لِیگاتورها رندر شود یا نه.<br/> وقتی به `true` تنظیم شود، لِیگاتورها در خروجی رندر شده غیرفعال می‌شوند. به‌طور پیش‌فرض، این ویژگی روی `false` تنظیم شده است. |
| [`warning_callback`](/slides/python-net/fa/aspose.slides.export/isvgoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/fa/aspose.slides.export/isvgoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/fa/aspose.slides.export/isvgoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/fa/aspose.slides.export/isvgoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/fa/aspose.slides.export/isvgoptions/skip_java_script_links/) |  |

### موارد مرتبط
* ماژول [`aspose.slides.export`](/slides/python-net/fa/aspose.slides.export)
* کتابخانه [`Aspose.Slides`](/slides/python-net)