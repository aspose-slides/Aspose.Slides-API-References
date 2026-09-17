---
title: ITiffOptions class
second_title: مرجع API Aspose.Slides للـ Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides.export/itiffoptions/
---
## ITiffOptions فئة

توفر خيارات تتحكم في كيفية حفظ العرض التقديمي بصيغة TIFF.

يعرض نوع ITiffOptions الأعضاء التالية:

## الخصائص

| خاصية | الوصف |
| :- | :- |
| [`image_size`](/slides/python-net/ar/aspose.slides.export/itiffoptions/image_size/) | يحدد حجم صورة TIFF المُنشأة.<br/>            القيمة الافتراضية هي 0x0، مما يعني أنه سيتم حساب أحجام الصور المُنشأة استنادًا إلى قيمة حجم شريحة العرض التقديمي.<br/>            قراءة/كتابة **aspose.slides.Size**. |
| [`dpi_x`](/slides/python-net/ar/aspose.slides.export/itiffoptions/dpi_x/) | يحدد الدقة الأفقية بوحدات النقاط لكل بوصة.<br/>            قراءة/كتابة **int**. |
| [`dpi_y`](/slides/python-net/ar/aspose.slides.export/itiffoptions/dpi_y/) | يحدد الدقة العمودية بوحدات النقاط لكل بوصة.<br/>            قراءة/كتابة **int**. |
| [`show_hidden_slides`](/slides/python-net/ar/aspose.slides.export/itiffoptions/show_hidden_slides/) | يحدد ما إذا كان يجب أن يتضمن المستند المُنشأ الشرائح المخفية أم لا.<br/>            القيمة الافتراضية هي `false`. |
| [`compression_type`](/slides/python-net/ar/aspose.slides.export/itiffoptions/compression_type/) | يحدد نوع الضغط.<br/>            قراءة/كتابة [`TiffCompressionTypes`](/slides/python-net/ar/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/ar/aspose.slides.export/itiffoptions/pixel_format/) | يحدد تنسيق البكسل للصور المُنشأة.<br/>            قراءة/كتابة [`ImagePixelFormat`](/slides/python-net/ar/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/ar/aspose.slides.export/itiffoptions/slides_layout_options/) | يحصل على أو يضبط الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [`ISlidesLayoutOptions`](/slides/python-net/ar/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/ar/aspose.slides.export/itiffoptions/bw_conversion_mode/) | يحدد الخوارزمية لتحويل صورة ملونة إلى صورة بالأبيض والأسود.<br/>            يُطبق هذا الخيار فقط إذا كان [`ITiffOptions.compression_type`](/slides/python-net/ar/aspose.slides.export/itiffoptions/compression_type) <br/>            مضبوطًا على [`TiffCompressionTypes.CCITT4`](/slides/python-net/ar/aspose.slides.export/tiffcompressiontypes/CCITT4) أو [`TiffCompressionTypes.CCITT3`](/slides/python-net/ar/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            قراءة/كتابة [`BlackWhiteConversionMode`](/slides/python-net/ar/aspose.slides.export/blackwhiteconversionmode).<br/>            القيمة الافتراضية هي [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/ar/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |
| [`ink_options`](/slides/python-net/ar/aspose.slides.export/itiffoptions/ink_options/) | توفر خيارات تتحكم بمظهر كائنات الحبر في المستند المُصدّر.<br/>            قراءة-فقط [`IInkOptions`](/slides/python-net/ar/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/ar/aspose.slides.export/itiffoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/ar/aspose.slides.export/itiffoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/ar/aspose.slides.export/itiffoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/ar/aspose.slides.export/itiffoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/ar/aspose.slides.export/itiffoptions/skip_java_script_links/) |  |

### انظر أيضًا
* وحدة [`aspose.slides.export`](/slides/python-net/ar/aspose.slides.export)
* مكتبة [`Aspose.Slides`](/slides/python-net)