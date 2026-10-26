---
title: TiffOptions class
second_title: Aspose.Slides برای Python از طریق .NET API مرجع
description: 
type: docs
url: /fa/aspose.slides.export/tiffoptions/
---
## TiffOptions کلاس

گزینه‌هایی را فراهم می‌کند که نحوه ذخیره ارائه در فرمت TIFF را کنترل می‌کند.

**وراثت:**[`TiffOptions`](/slides/python-net/fa/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/fa/aspose.slides.export/saveoptions)

نوع TiffOptions اعضای زیر را عرضه می‌کند:

## سازنده‌ها

| سازنده | توضیح |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fa/aspose.slides.export/tiffoptions/__init__/#) | سازندهٔ پیش‌فرض. |

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`warning_callback`](/slides/python-net/fa/aspose.slides.export/tiffoptions/warning_callback/) | مقدار بازگردانده شده یا تنظیم یک شیئی که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود.<br/>            خواندنی/نوشتنی [`IWarningCallback`](/slides/python-net/fa/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/fa/aspose.slides.export/tiffoptions/progress_callback/) | یک شیء callback را برای به‌روزرسانی پیشرفت ذخیره‌سازی به درصد نشان می‌دهد.<br/>            نگاه کنید به [`IProgressCallback`](/slides/python-net/fa/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/fa/aspose.slides.export/tiffoptions/default_regular_font/) | قلمی را که در صورت یافت نشدن قلم منبع استفاده می‌شود، بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **str**. |
| [`gradient_style`](/slides/python-net/fa/aspose.slides.export/tiffoptions/gradient_style/) | سبک بصری گرادیان را بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی [`GradientStyle`](/slides/python-net/fa/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/fa/aspose.slides.export/tiffoptions/skip_java_script_links/) | مشخص می‌کند که هنگام ذخیره‌سازی ارائه، آیا پیوندهای هیپر که فراخوانی‌های JavaScript دارند، نادیده گرفته شوند یا نه.<br/>            خواندنی/نوشتنی **bool**. مقدار پیش‌فرض **false** است. |
| [`ink_options`](/slides/python-net/fa/aspose.slides.export/tiffoptions/ink_options/) | گزینه‌هایی را فراهم می‌کند که ظاهر اشیای Ink را در سند صادرشده کنترل می‌کند.<br/>            فقط‌خواندنی [`IInkOptions`](/slides/python-net/fa/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/fa/aspose.slides.export/tiffoptions/show_hidden_slides/) | مشخص می‌کند که سند تولید شده آیا اسلایدهای پنهان را شامل شود یا نه.<br/>            مقدار پیش‌فرض `false` است. |
| [`image_size`](/slides/python-net/fa/aspose.slides.export/tiffoptions/image_size/) | اندازه یک تصویر TIFF تولید شده را مشخص می‌کند.<br/>            مقدار پیش‌فرض 0x0 است، که به این معناست که اندازه تصاویر تولید شده بر پایه مقدار اندازه اسلاید ارائه محاسبه می‌شود.<br/>            خواندنی/نوشتنی [`Size`](/slides/python-net/fa/aspose.slides/size). |
| [`dpi_x`](/slides/python-net/fa/aspose.slides.export/tiffoptions/dpi_x/) | وضوح افقی را به نقطه در اینچ مشخص می‌کند.<br/>            خواندنی/نوشتنی **int**. |
| [`dpi_y`](/slides/python-net/fa/aspose.slides.export/tiffoptions/dpi_y/) | وضوح عمودی را به نقطه در اینچ مشخص می‌کند.<br/>            خواندنی/نوشتنی **int**. |
| [`compression_type`](/slides/python-net/fa/aspose.slides.export/tiffoptions/compression_type/) | نوع فشرده‌سازی را مشخص می‌کند.<br/>            خواندنی/نوشتنی [`TiffCompressionTypes`](/slides/python-net/fa/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/fa/aspose.slides.export/tiffoptions/pixel_format/) | قالب پیکسل برای تصاویر تولید شده را مشخص می‌کند.<br/>            خواندنی/نوشتنی [`ImagePixelFormat`](/slides/python-net/fa/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/fa/aspose.slides.export/tiffoptions/slides_layout_options/) | حالت قرارگیری اسلایدها روی صفحه هنگام صادرات ارائه را دریافت یا تنظیم می‌کند [`ISlidesLayoutOptions`](/slides/python-net/fa/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/fa/aspose.slides.export/tiffoptions/bw_conversion_mode/) | الگوریتم تبدیل تصویر رنگی به تصویر سیاه و سفید را مشخص می‌کند.<br/>            این گزینه فقط در صورتی اعمال می‌شود که [`TiffOptions.compression_type`](/slides/python-net/fa/aspose.slides.export/tiffoptions/compression_type)<br/>            بر روی [`TiffCompressionTypes.CCITT4`](/slides/python-net/fa/aspose.slides.export/tiffcompressiontypes/CCITT4) یا [`TiffCompressionTypes.CCITT3`](/slides/python-net/fa/aspose.slides.export/tiffcompressiontypes/CCITT3) تنظیم شده باشد<br/>            خواندنی/نوشتنی [`BlackWhiteConversionMode`](/slides/python-net/fa/aspose.slides.export/blackwhiteconversionmode).<br/>            مقدار پیش‌فرض [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/fa/aspose.slides.export/blackwhiteconversionmode/DEFAULT) است. |


### موارد مرتبط
* کلاس [`SaveOptions`](/slides/python-net/fa/aspose.slides.export/saveoptions)
* کلاس [`TiffOptions`](/slides/python-net/fa/aspose.slides.export/tiffoptions)
* ماژول [`aspose.slides.export`](/slides/python-net/fa/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)