---
title: SVGOptions class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.export/svgoptions/
---
## SVGOptions کلاس

نمایانگر یک گزینه SVG است.

**Inheritance:**[`SVGOptions`](/slides/python-net/fa/aspose.slides.export/svgoptions) → [`SaveOptions`](/slides/python-net/fa/aspose.slides.export/saveoptions)

نوع SVGOptions اعضای زیر را ارائه می‌دهد:

## سازنده‌ها

| سازنده | توضیح |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fa/aspose.slides.export/svgoptions/__init__/#) | یک نمونه جدید از کلاس SVGOptions را مقداردهی اولیه می‌کند. |
| [`__init__(self, link_embed_controller)`](/slides/python-net/fa/aspose.slides.export/svgoptions/__init__/#ilinkembedcontroller) | یک نمونه جدید از کلاس SVGOptions را با تعیین شیء کنترل‌کننده تعبیه‌لینک مقداردهی اولیه می‌کند. |

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`warning_callback`](/slides/python-net/fa/aspose.slides.export/svgoptions/warning_callback/) | یک شیء را که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا لغو شود، برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندن/نوشتن [`IWarningCallback`](/slides/python-net/fa/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/fa/aspose.slides.export/svgoptions/progress_callback/) | یک شیء بازخوانی (callback) را برای ذخیره‌سازی به‌روزرسانی‌های پیشرفت به درصد نمایندگی می‌کند.<br/>            به [`IProgressCallback`](/slides/python-net/fa/aspose.slides/iprogresscallback) مراجعه کنید. |
| [`default_regular_font`](/slides/python-net/fa/aspose.slides.export/svgoptions/default_regular_font/) | فونتی را که در صورت عدم یافتن فونت منبع استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندن/نوشتن **str**. |
| [`gradient_style`](/slides/python-net/fa/aspose.slides.export/svgoptions/gradient_style/) | سبک بصری گرادیان را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندن/نوشتن [`GradientStyle`](/slides/python-net/fa/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/fa/aspose.slides.export/svgoptions/skip_java_script_links/) | مشخص می‌کند آیا هنگام ذخیره‌سازی ارائه، پیوندهای با فراخوانی‌های JavaScript نادیده گرفته شوند یا نه.<br/>            خواندن/نوشتن **bool**. مقدار پیش‌فرض **false** است. |
| [`ink_options`](/slides/python-net/fa/aspose.slides.export/svgoptions/ink_options/) | گزینه‌هایی را فراهم می‌کند که ظاهر اشیای Ink را در سند صادرشده کنترل می‌کنند.<br/>            فقط‌خواندنی [`IInkOptions`](/slides/python-net/fa/aspose.slides.export/iinkoptions) |
| [`use_frame_size`](/slides/python-net/fa/aspose.slides.export/svgoptions/use_frame_size/) | تعیین می‌کند آیا فریم متن در ناحیه رندر گنجانده شود یا نه.<br/>            خواندن/نوشتن **bool**.<br/>            مقدار پیش‌فرض false است. |
| [`use_frame_rotation`](/slides/python-net/fa/aspose.slides.export/svgoptions/use_frame_rotation/) | تعیین می‌کند آیا چرخش مشخص‌شده شکل هنگام رندر اعمال شود یا نه.<br/>            خواندن/نوشتن **bool**.<br/>            مقدار پیش‌فرض true است. |
| [`vectorize_text`](/slides/python-net/fa/aspose.slides.export/svgoptions/vectorize_text/) | تعیین می‌کند آیا متن روی اسلاید به‌صورت گرافیک ذخیره شود یا نه.<br/>            خواندن/نوشتن **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/fa/aspose.slides.export/svgoptions/metafile_rasterization_dpi/) | حد پایین وضوح برای رستر‌سازی متافایل را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندن/نوشتن **int**. |
| [`disable_3d_text`](/slides/python-net/fa/aspose.slides.export/svgoptions/disable_3d_text/) | تعیین می‌کند آیا متن 3D در SVG غیرفعال باشد یا نه.<br/>            خواندن/نوشتن **bool**. |
| [`disable_gradient_split`](/slides/python-net/fa/aspose.slides.export/svgoptions/disable_gradient_split/) | تقسیم گرادیان‌های FromCornerX و FromCenter را غیرفعال می‌کند.<br/>            خواندن/نوشتن **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/fa/aspose.slides.export/svgoptions/disable_line_end_cropping/) | SVG 1.1 قادر به تعریف حاشیه برای نشانگرها نیست.<br/>            موتور نوشتن SVG Aspose.Slides راه‌حلی برای این مشکل دارد:<br/>            انتهای خط را با پیکان برش می‌دهد، به‌طوری که خط با نشانگرها همپوشانی نداشته باشد.<br/>            این گزینه این رفتار را غیرفعال می‌کند.<br/>            خواندن/نوشتن **bool**. |
| [`default`](/slides/python-net/fa/aspose.slides.export/svgoptions/default/) | تنظیمات پیش‌فرض را برمی‌گرداند.<br/>            فقط‌خواندنی [`SVGOptions`](/slides/python-net/fa/aspose.slides.export/svgoptions). |
| [`simple`](/slides/python-net/fa/aspose.slides.export/svgoptions/simple/) | تنظیمات برای ساده‌ترین و کوچک‌ترین تولید فایل SVG را برمی‌گرداند.<br/>            فقط‌خواندنی [`SVGOptions`](/slides/python-net/fa/aspose.slides.export/svgoptions). |
| [`wysiwyg`](/slides/python-net/fa/aspose.slides.export/svgoptions/wysiwyg/) | تنظیمات برای دقیق‌ترین تولید فایل SVG را برمی‌گرداند.<br/>            فقط‌خواندنی [`SVGOptions`](/slides/python-net/fa/aspose.slides.export/svgoptions). |
| [`jpeg_quality`](/slides/python-net/fa/aspose.slides.export/svgoptions/jpeg_quality/) | کیفیت رمزگذاری JPEG را تعیین می‌کند.<br/>            خواندن/نوشتن **int**. |
| [`shape_formatting_controller`](/slides/python-net/fa/aspose.slides.export/svgoptions/shape_formatting_controller/) | یک رابط بازخوانی (callback) که به کاربر اجازه کنترل تبدیل شکل را می‌دهد، برمی‌گرداند و تنظیم می‌کند.<br/>            خواندن/نوشتن [`ISvgShapeFormattingController`](/slides/python-net/fa/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/fa/aspose.slides.export/svgoptions/pictures_compression/) | سطح فشرده‌سازی تصاویر را نمایندگی می‌کند |
| [`delete_pictures_cropped_areas`](/slides/python-net/fa/aspose.slides.export/svgoptions/delete_pictures_cropped_areas/) | پرچم بولی نشان می‌دهد آیا بخش‌های برش‌خورده به‌عنوان بخشی از سند باقی می‌مانند یا نه. اگر true باشد، بخش‌های برش‌خورده <br/>            حذف می‌شوند، اگر false باشند، در سند سریال‌سازی می‌شوند (که می‌تواند منجر به <br/>            فایل بزرگ‌تر شود) |
| [`external_fonts_handling`](/slides/python-net/fa/aspose.slides.export/svgoptions/external_fonts_handling/) | راهی برای مدیریت فونت‌های بارگذاری‌شده به‌صورت خارجی تعیین می‌کند.<br/>            خواندن/نوشتن [`SvgExternalFontsHandling`](/slides/python-net/fa/aspose.slides.export/svgexternalfontshandling). |
| [`disable_font_ligatures`](/slides/python-net/fa/aspose.slides.export/svgoptions/disable_font_ligatures/) | مقداری را که نشان می‌دهد آیا متن بدون استفاده از لیگاتورها رندر می‌شود یا نه، برمی‌گرداند یا تنظیم می‌کند.<br/>            وقتی به `true` تنظیم شود، لیگاتورها در خروجی رندر شده غیرفعال می‌شوند. به‌طور پیش‌فرض، این ویژگی به `false` تنظیم شده است. |

### موارد مرتبط
* کلاس [`SaveOptions`](/slides/python-net/fa/aspose.slides.export/saveoptions)
* کلاس [`SVGOptions`](/slides/python-net/fa/aspose.slides.export/svgoptions)
* ماژول [`aspose.slides.export`](/slides/python-net/fa/aspose.slides.export)
* کتابخانه [`Aspose.Slides`](/slides/python-net)