---
title: ITiffOptions class
second_title: Aspose.Slides برای پایتون از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.export/itiffoptions/
---
## ITiffOptions کلاس

گزینه‌هایی را فراهم می‌کند که نحوهٔ ذخیرهٔ یک ارائه در فرمت TIFF را کنترل می‌کند.

نوع ITiffOptions اعضای زیر را در دسترس می‌گذارد:

## خصوصیات

| ویژگی | توضیح |
| :- | :- |
| [`image_size`](/slides/python-net/fa/aspose.slides.export/itiffoptions/image_size/) | اندازهٔ یک تصویر TIFF تولید شده را مشخص می‌کند.<br/>            مقدار پیش‌فرض 0x0 است، که به این معنی است که اندازهٔ تصاویر تولید شده بر اساس مقدار اندازهٔ اسلاید ارائه محاسبه می‌شود.<br/>            خواندن/نوشتن [`Size`](/slides/python-net/fa/aspose.slides/size). |
| [`dpi_x`](/slides/python-net/fa/aspose.slides.export/itiffoptions/dpi_x/) | رزولوشن افقی را بر حسب نقطه در اینچ مشخص می‌کند.<br/>            خواندن/نوشتن **int**. |
| [`dpi_y`](/slides/python-net/fa/aspose.slides.export/itiffoptions/dpi_y/) | رزولوشن عمودی را بر حسب نقطه در اینچ مشخص می‌کند.<br/>            خواندن/نوشتن **int**. |
| [`show_hidden_slides`](/slides/python-net/fa/aspose.slides.export/itiffoptions/show_hidden_slides/) | مشخص می‌کند که آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه.<br/>            مقدار پیش‌فرض `false` است. |
| [`compression_type`](/slides/python-net/fa/aspose.slides.export/itiffoptions/compression_type/) | نوع فشرده‌سازی را مشخص می‌کند.<br/>            خواندن/نوشتن [`TiffCompressionTypes`](/slides/python-net/fa/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/fa/aspose.slides.export/itiffoptions/pixel_format/) | قالب پیکسل برای تصاویر تولید شده را مشخص می‌کند.<br/>            خواندن/نوشتن [`ImagePixelFormat`](/slides/python-net/fa/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/fa/aspose.slides.export/itiffoptions/slides_layout_options/) | حالت قرارگیری اسلایدها بر روی صفحه هنگام استخراج یک ارائه را دریافت یا تنظیم می‌کند [`ISlidesLayoutOptions`](/slides/python-net/fa/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/fa/aspose.slides.export/itiffoptions/bw_conversion_mode/) | الگوریتم تبدیل یک تصویر رنگی به تصویر سیاه-سفید را مشخص می‌کند.<br/>            این گزینه فقط در صورتی اعمال می‌شود که [`ITiffOptions.compression_type`](/slides/python-net/fa/aspose.slides.export/itiffoptions/compression_type) <br/>            به [`TiffCompressionTypes.CCITT4`](/slides/python-net/fa/aspose.slides.export/tiffcompressiontypes/CCITT4) یا [`TiffCompressionTypes.CCITT3`](/slides/python-net/fa/aspose.slides.export/tiffcompressiontypes/CCITT3) تنظیم شده باشد<br/>            خواندن/نوشتن [`BlackWhiteConversionMode`](/slides/python-net/fa/aspose.slides.export/blackwhiteconversionmode).<br/>            مقدار پیش‌فرض [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/fa/aspose.slides.export/blackwhiteconversionmode/DEFAULT) است. |
| [`ink_options`](/slides/python-net/fa/aspose.slides.export/itiffoptions/ink_options/) | گزینه‌هایی را فراهم می‌کند که ظاهر اشیاء Ink در سند صادر شده را کنترل می‌کند.<br/>            فقط خواندنی [`IInkOptions`](/slides/python-net/fa/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/fa/aspose.slides.export/itiffoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/fa/aspose.slides.export/itiffoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/fa/aspose.slides.export/itiffoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/fa/aspose.slides.export/itiffoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/fa/aspose.slides.export/itiffoptions/skip_java_script_links/) |  |


### موارد مرتبط
* ماژول [`aspose.slides.export`](/slides/python-net/fa/aspose.slides.export)
* کتابخانه [`Aspose.Slides`](/slides/python-net)