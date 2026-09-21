---
title: ITiffOptions class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.export/itiffoptions/
---
## کلاس ITiffOptions

گزینه‌هایی را فراهم می‌کند که نحوه ذخیره‌سازی یک ارائه را در قالب TIFF کنترل می‌کند.

نوع ITiffOptions اعضای زیر را نمایش می‌دهد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`image_size`](/slides/python-net/fa/aspose.slides.export/itiffoptions/image_size/) | اندازه تصویر تولید شده TIFF را مشخص می‌کند.<br/>            مقدار پیش‌فرض 0x0 است، که به این معناست که اندازه‌های تصویر تولید شده بر اساس مقدار اندازه اسلاید ارائه محاسبه می‌شود.<br/>            خواندنی/نوشتنی **aspose.slides.Size**. |
| [`dpi_x`](/slides/python-net/fa/aspose.slides.export/itiffoptions/dpi_x/) | وضوح افقی را بر حسب نقطه در اینچ مشخص می‌کند.<br/>            خواندنی/نوشتنی **int**. |
| [`dpi_y`](/slides/python-net/fa/aspose.slides.export/itiffoptions/dpi_y/) | وضوح عمودی را بر حسب نقطه در اینچ مشخص می‌کند.<br/>            خواندنی/نوشتنی **int**. |
| [`show_hidden_slides`](/slides/python-net/fa/aspose.slides.export/itiffoptions/show_hidden_slides/) | مشخص می‌کند که آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا خیر.<br/>            مقدار پیش‌فرض `false` است. |
| [`compression_type`](/slides/python-net/fa/aspose.slides.export/itiffoptions/compression_type/) | نوع فشرده‌سازی را مشخص می‌کند.<br/>            خواندنی/نوشتنی [`TiffCompressionTypes`](/slides/python-net/fa/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/fa/aspose.slides.export/itiffoptions/pixel_format/) | قالب پیکسل برای تصاویر تولید شده را مشخص می‌کند.<br/>            خواندنی/نوشتنی [`ImagePixelFormat`](/slides/python-net/fa/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/fa/aspose.slides.export/itiffoptions/slides_layout_options/) | حالت قرارگیری اسلایدها در صفحه هنگام استخراج یک ارائه [`ISlidesLayoutOptions`](/slides/python-net/fa/aspose.slides.export/islideslayoutoptions) را دریافت یا تنظیم می‌کند. |
| [`bw_conversion_mode`](/slides/python-net/fa/aspose.slides.export/itiffoptions/bw_conversion_mode/) | الگوریتم تبدیل یک تصویر رنگی به تصویر سیاه-سفید را مشخص می‌کند.<br/>            این گزینه تنها زمانی اعمال می‌شود که [`ITiffOptions.compression_type`](/slides/python-net/fa/aspose.slides.export/itiffoptions/compression_type) <br/>            روی [`TiffCompressionTypes.CCITT4`](/slides/python-net/fa/aspose.slides.export/tiffcompressiontypes/CCITT4) یا [`TiffCompressionTypes.CCITT3`](/slides/python-net/fa/aspose.slides.export/tiffcompressiontypes/CCITT3) تنظیم شده باشد<br/>            خواندنی/نوشتنی [`BlackWhiteConversionMode`](/slides/python-net/fa/aspose.slides.export/blackwhiteconversionmode).<br/>            مقدار پیش‌فرض [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/fa/aspose.slides.export/blackwhiteconversionmode/DEFAULT) است. |
| [`ink_options`](/slides/python-net/fa/aspose.slides.export/itiffoptions/ink_options/) | گزینه‌هایی را فراهم می‌کند که ظاهر اشیاء Ink را در سند استخراج شده کنترل می‌کند.<br/>            فقط‌خواندنی [`IInkOptions`](/slides/python-net/fa/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/fa/aspose.slides.export/itiffoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/fa/aspose.slides.export/itiffoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/fa/aspose.slides.export/itiffoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/fa/aspose.slides.export/itiffoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/fa/aspose.slides.export/itiffoptions/skip_java_script_links/) |  |

### مطالب مرتبط
* ماژول [`aspose.slides.export`](/slides/python-net/fa/aspose.slides.export)
* کتابخانه [`Aspose.Slides`](/slides/python-net)