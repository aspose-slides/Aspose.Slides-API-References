---
title: TiffOptions class
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.export/tiffoptions/
---
## فئة TiffOptions

يوفر خيارات تتحكم في كيفية حفظ العرض التقديمي بتنسيق TIFF.

**الوراثة:**[`TiffOptions`](/slides/python-net/ar/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/ar/aspose.slides.export/saveoptions)

نوع TiffOptions يعرض الأعضاء التالية:

## المنشئون

| المنشيء | الوصف |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ar/aspose.slides.export/tiffoptions/__init__/#) | المُنشئ الافتراضي. |

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`warning_callback`](/slides/python-net/ar/aspose.slides.export/tiffoptions/warning_callback/) | يرجع أو يضبط كائنًا يستقبل التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أم سيتم إلغاؤها.<br/>            قراءة/كتابة [`IWarningCallback`](/slides/python-net/ar/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ar/aspose.slides.export/tiffoptions/progress_callback/) | يمثل كائنًا استدعاءً خلفيًا لتحديثات تقدم الحفظ بالنسبة المئوية.<br/>            راجع [`IProgressCallback`](/slides/python-net/ar/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ar/aspose.slides.export/tiffoptions/default_regular_font/) | يرجع أو يضبط الخط المستخدم في حال عدم العثور على الخط المصدر.<br/>            قراءة/كتابة **str**. |
| [`gradient_style`](/slides/python-net/ar/aspose.slides.export/tiffoptions/gradient_style/) | يرجع أو يضبط النمط البصري للتدرج.<br/>            قراءة/كتابة [`GradientStyle`](/slides/python-net/ar/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ar/aspose.slides.export/tiffoptions/skip_java_script_links/) | يحدد ما إذا كان سيتم تخطي الروابط الفائقة التي تحتوي على استدعاءات JavaScript عند حفظ العرض التقديمي.<br/>            قراءة/كتابة **bool**. القيمة الافتراضية هي **false**. |
| [`ink_options`](/slides/python-net/ar/aspose.slides.export/tiffoptions/ink_options/) | يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدَّر.<br/>            قراءة فقط [`IInkOptions`](/slides/python-net/ar/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/ar/aspose.slides.export/tiffoptions/show_hidden_slides/) | يحدد ما إذا كان المستند المُولَّد يجب أن يتضمن الشرائح المخفية أم لا.<br/>            القيمة الافتراضية هي `false`. |
| [`image_size`](/slides/python-net/ar/aspose.slides.export/tiffoptions/image_size/) | يحدد حجم الصورة TIFF المُولَّدة.<br/>            القيمة الافتراضية هي 0x0، ما يعني أن أحجام الصور المُولَّدة ستحسب بناءً على قيمة حجم شريحة العرض.<br/>            قراءة/كتابة [`Size`](/slides/python-net/ar/aspose.slides/size). |
| [`dpi_x`](/slides/python-net/ar/aspose.slides.export/tiffoptions/dpi_x/) | يحدد دقة الأفقية بالنقاط في البوصة.<br/>            قراءة/كتابة **int**. |
| [`dpi_y`](/slides/python-net/ar/aspose.slides.export/tiffoptions/dpi_y/) | يحدد دقة العمودية بالنقاط في البوصة.<br/>            قراءة/كتابة **int**. |
| [`compression_type`](/slides/python-net/ar/aspose.slides.export/tiffoptions/compression_type/) | يحدد نوع الضغط.<br/>            قراءة/كتابة [`TiffCompressionTypes`](/slides/python-net/ar/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/ar/aspose.slides.export/tiffoptions/pixel_format/) | يحدد تنسيق البكسل للصور المُولَّدة.<br/>            قراءة/كتابة [`ImagePixelFormat`](/slides/python-net/ar/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/ar/aspose.slides.export/tiffoptions/slides_layout_options/) | يرجع أو يضبط الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [`ISlidesLayoutOptions`](/slides/python-net/ar/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/ar/aspose.slides.export/tiffoptions/bw_conversion_mode/) | يحدد الخوارزمية لتحويل صورة ملونة إلى صورة بالأبيض والأسود.<br/>            سيُطبق هذا الخيار فقط إذا كان [`TiffOptions.compression_type`](/slides/python-net/ar/aspose.slides.export/tiffoptions/compression_type) <br/>            مضبوطًا على [`TiffCompressionTypes.CCITT4`](/slides/python-net/ar/aspose.slides.export/tiffcompressiontypes/CCITT4) أو [`TiffCompressionTypes.CCITT3`](/slides/python-net/ar/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            قراءة/كتابة [`BlackWhiteConversionMode`](/slides/python-net/ar/aspose.slides.export/blackwhiteconversionmode).<br/>            القيمة الافتراضية هي [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/ar/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |

### انظر أيضًا
* فئة [`SaveOptions`](/slides/python-net/ar/aspose.slides.export/saveoptions)
* فئة [`TiffOptions`](/slides/python-net/ar/aspose.slides.export/tiffoptions)
* وحدة [`aspose.slides.export`](/slides/python-net/ar/aspose.slides.export)
* مكتبة [`Aspose.Slides`](/slides/python-net)