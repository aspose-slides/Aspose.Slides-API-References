---
title: TiffOptions class
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.export/tiffoptions/
---
## فئة TiffOptions

يقدم خيارات تتحكم في طريقة حفظ العرض التقديمي بصيغة TIFF.

**Inheritance:**[`TiffOptions`](/slides/python-net/ar/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/ar/aspose.slides.export/saveoptions)

نوع TiffOptions يكشف عن الأعضاء التالية:

## المنشئات

| منشئ | الوصف |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ar/aspose.slides.export/tiffoptions/__init__/#) | منشئ افتراضي. |

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`warning_callback`](/slides/python-net/ar/aspose.slides.export/tiffoptions/warning_callback/) | إرجاع أو تعيين كائن يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو ستُلغى.<br/>            قراءة/كتابة [`IWarningCallback`](/slides/python-net/ar/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ar/aspose.slides.export/tiffoptions/progress_callback/) | يمثل كائن استدعاء للارتداد لتحديثات تقدم الحفظ بالنسبة المئوية.<br/>            راجع [`IProgressCallback`](/slides/python-net/ar/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ar/aspose.slides.export/tiffoptions/default_regular_font/) | إرجاع أو تعيين الخط المستخدم إذا لم يتم العثور على الخط المصدر.<br/>            قراءة/كتابة **str**. |
| [`gradient_style`](/slides/python-net/ar/aspose.slides.export/tiffoptions/gradient_style/) | إرجاع أو تعيين النمط البصري للتدرج اللوني.<br/>            قراءة/كتابة [`GradientStyle`](/slides/python-net/ar/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ar/aspose.slides.export/tiffoptions/skip_java_script_links/) | يحدد ما إذا كان يجب تخطي الروابط التشعبية التي تحتوي على نداءات JavaScript عند حفظ العرض التقديمي.<br/>            قراءة/كتابة **bool**. القيمة الافتراضية هي **false** . |
| [`ink_options`](/slides/python-net/ar/aspose.slides.export/tiffoptions/ink_options/) | يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المصدر.<br/>            قراءة فقط [`IInkOptions`](/slides/python-net/ar/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/ar/aspose.slides.export/tiffoptions/show_hidden_slides/) | يحدد ما إذا كان المستند المُولَّد يجب أن يتضمن الشرائح المخفية أم لا.<br/>            القيمة الافتراضية هي `false`. |
| [`image_size`](/slides/python-net/ar/aspose.slides.export/tiffoptions/image_size/) | يحدد حجم صورة TIFF المُولَّدة.<br/>            القيمة الافتراضية هي 0x0، ما يعني أن أحجام الصور المُولَّدة سُتحسب بناءً على قيمة حجم شريحة العرض التقديمي.<br/>            قراءة/كتابة **aspose.slides.Size**. |
| [`dpi_x`](/slides/python-net/ar/aspose.slides.export/tiffoptions/dpi_x/) | يحدد الدقة الأفقية بالنقاط لكل بوصة.<br/>            قراءة/كتابة **int**. |
| [`dpi_y`](/slides/python-net/ar/aspose.slides.export/tiffoptions/dpi_y/) | يحدد الدقة العمودية بالنقاط لكل بوصة.<br/>            قراءة/كتابة **int**. |
| [`compression_type`](/slides/python-net/ar/aspose.slides.export/tiffoptions/compression_type/) | يحدد نوع الضغط.<br/>            قراءة/كتابة [`TiffCompressionTypes`](/slides/python-net/ar/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/ar/aspose.slides.export/tiffoptions/pixel_format/) | يحدد تنسيق البكسل للصور المُولَّدة.<br/>            قراءة/كتابة [`ImagePixelFormat`](/slides/python-net/ar/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/ar/aspose.slides.export/tiffoptions/slides_layout_options/) | إرجاع أو تعيين الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير العرض التقديمي [`ISlidesLayoutOptions`](/slides/python-net/ar/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/ar/aspose.slides.export/tiffoptions/bw_conversion_mode/) | يحدد الخوارزمية لتحويل صورة ملونة إلى صورة أبيض وأسود.<br/>            سيُطبق هذا الخيار فقط إذا كان [`TiffOptions.compression_type`](/slides/python-net/ar/aspose.slides.export/tiffoptions/compression_type) <br/>            معيينًا إلى [`TiffCompressionTypes.CCITT4`](/slides/python-net/ar/aspose.slides.export/tiffcompressiontypes/CCITT4) أو [`TiffCompressionTypes.CCITT3`](/slides/python-net/ar/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            قراءة/كتابة [`BlackWhiteConversionMode`](/slides/python-net/ar/aspose.slides.export/blackwhiteconversionmode).<br/>            القيمة الافتراضية هي [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/ar/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |


### انظر أيضًا
* فئة [`SaveOptions`](/slides/python-net/ar/aspose.slides.export/saveoptions)
* فئة [`TiffOptions`](/slides/python-net/ar/aspose.slides.export/tiffoptions)
* وحدة [`aspose.slides.export`](/slides/python-net/ar/aspose.slides.export)
* مكتبة [`Aspose.Slides`](/slides/python-net)