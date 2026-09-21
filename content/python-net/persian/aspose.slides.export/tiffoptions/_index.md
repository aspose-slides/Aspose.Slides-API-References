---
title: TiffOptions class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.export/tiffoptions/
---
## TiffOptions کلاس

گزینه‌هایی را فراهم می‌کند که نحوه ذخیره‌سازی یک ارائه در فرمت TIFF را کنترل می‌کند.

**Inheritance:**[`TiffOptions`](/slides/python-net/fa/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/fa/aspose.slides.export/saveoptions)

The TiffOptions type exposes the following members:

## سازنده‌ها

| سازنده | توضیح |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fa/aspose.slides.export/tiffoptions/__init__/#) | Default constructor. |

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`warning_callback`](/slides/python-net/fa/aspose.slides.export/tiffoptions/warning_callback/) | دریافت یا تنظیم شیئی که هشدارها را دریافت می‌کند و تصمیم می‌گیرد فرآیند بارگذاری ادامه یابد یا لغو شود.<br/>            خواندنی/نوشتنی [`IWarningCallback`](/slides/python-net/fa/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/fa/aspose.slides.export/tiffoptions/progress_callback/) | نمایشی از یک شیء فراخوانی برای به‌روزرسانی‌های پیشرفت ذخیره‌سازی به درصد.<br/>            See [`IProgressCallback`](/slides/python-net/fa/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/fa/aspose.slides.export/tiffoptions/default_regular_font/) | دریافت یا تنظیم قلم مورد استفاده در صورتی که قلم منبع پیدا نشود.<br/>            خواندنی/نوشتنی **str**. |
| [`gradient_style`](/slides/python-net/fa/aspose.slides.export/tiffoptions/gradient_style/) | دریافت یا تنظیم سبک بصری گرادیان.<br/>            خواندنی/نوشتنی [`GradientStyle`](/slides/python-net/fa/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/fa/aspose.slides.export/tiffoptions/skip_java_script_links/) | مشخص می‌کند که آیا هنگام ذخیره‌سازی ارائه، پیوندهای هیپرتکست دارای فراخوانی‌های JavaScript نادیده گرفته شوند یا نه.<br/>            خواندنی/نوشتنی **bool**. مقدار پیش‌فرض **false** است. |
| [`ink_options`](/slides/python-net/fa/aspose.slides.export/tiffoptions/ink_options/) | گزینه‌هایی را فراهم می‌کند که ظاهر اشیاء Ink را در سند صادر شده کنترل می‌کند.<br/>            فقط-خواندنی [`IInkOptions`](/slides/python-net/fa/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/fa/aspose.slides.export/tiffoptions/show_hidden_slides/) | مشخص می‌کند که آیا سند تولید شده باید اسلایدهای پنهان را شامل شود یا خیر.<br/>            مقدار پیش‌فرض `false` است. |
| [`image_size`](/slides/python-net/fa/aspose.slides.export/tiffoptions/image_size/) | اندازه تصویر TIFF تولید شده را مشخص می‌کند.<br/>            مقدار پیش‌فرض 0x0 است که به این معنی است که اندازه‌های تصویر تولید شده بر اساس مقدار اندازه اسلاید ارائه محاسبه می‌شود.<br/>            خواندنی/نوشتنی **aspose.slides.Size**. |
| [`dpi_x`](/slides/python-net/fa/aspose.slides.export/tiffoptions/dpi_x/) | وضوح افقی را به نقطه در اینچ مشخص می‌کند.<br/>            خواندنی/نوشتنی **int**. |
| [`dpi_y`](/slides/python-net/fa/aspose.slides.export/tiffoptions/dpi_y/) | وضوح عمودی را به نقطه در اینچ مشخص می‌کند.<br/>            خواندنی/نوشتنی **int**. |
| [`compression_type`](/slides/python-net/fa/aspose.slides.export/tiffoptions/compression_type/) | نوع فشرده‌سازی را مشخص می‌کند.<br/>            خواندنی/نوشتنی [`TiffCompressionTypes`](/slides/python-net/fa/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/fa/aspose.slides.export/tiffoptions/pixel_format/) | قالب پیکسل برای تصاویر تولید شده را مشخص می‌کند.<br/>            خواندنی/نوشتنی [`ImagePixelFormat`](/slides/python-net/fa/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/fa/aspose.slides.export/tiffoptions/slides_layout_options/) | دریافت یا تنظیم حالت قرارگیری اسلایدها روی صفحه هنگام صادرات ارائه [`ISlidesLayoutOptions`](/slides/python-net/fa/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/fa/aspose.slides.export/tiffoptions/bw_conversion_mode/) | الگوریتم تبدیل تصویر رنگی به تصویر سیاه-سفید را مشخص می‌کند.<br/>            این گزینه تنها زمانی اعمال می‌شود که [`TiffOptions.compression_type`](/slides/python-net/fa/aspose.slides.export/tiffoptions/compression_type) <br/>            برابر [`TiffCompressionTypes.CCITT4`](/slides/python-net/fa/aspose.slides.export/tiffcompressiontypes/CCITT4) یا [`TiffCompressionTypes.CCITT3`](/slides/python-net/fa/aspose.slides.export/tiffcompressiontypes/CCITT3) باشد<br/>            خواندنی/نوشتنی [`BlackWhiteConversionMode`](/slides/python-net/fa/aspose.slides.export/blackwhiteconversionmode).<br/>            مقدار پیش‌فرض [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/fa/aspose.slides.export/blackwhiteconversionmode/DEFAULT) است. |

### مراجع
* کلاس [`SaveOptions`](/slides/python-net/fa/aspose.slides.export/saveoptions)
* کلاس [`TiffOptions`](/slides/python-net/fa/aspose.slides.export/tiffoptions)
* ماژول [`aspose.slides.export`](/slides/python-net/fa/aspose.slides.export)
* کتابخانه [`Aspose.Slides`](/slides/python-net)