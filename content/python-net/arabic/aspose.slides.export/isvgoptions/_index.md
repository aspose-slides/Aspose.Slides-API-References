---
title: ISVGOptions class
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.export/isvgoptions/
---
## ISVGOptions فئة

يمثل خيارات SVG.

يعرض نوع ISVGOptions الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`vectorize_text`](/slides/python-net/ar/aspose.slides.export/isvgoptions/vectorize_text/) | يحدد ما إذا كان النص على الشريحة سيُحفظ كرسومات.<br/>            قراءة/كتابة **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/ar/aspose.slides.export/isvgoptions/metafile_rasterization_dpi/) | يعيد أو يضبط الحد الأدنى لدقة rasterization للملف الوصفي.<br/>            قراءة/كتابة **int**. |
| [`disable_3d_text`](/slides/python-net/ar/aspose.slides.export/isvgoptions/disable_3d_text/) | يحدد ما إذا كان النص ثلاثي الأبعاد معطلاً في SVG.<br/>            قراءة/كتابة **bool**. |
| [`disable_gradient_split`](/slides/python-net/ar/aspose.slides.export/isvgoptions/disable_gradient_split/) | يعطل تقسيم التدرجات FromCornerX و FromCenter.<br/>            قراءة/كتابة **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/ar/aspose.slides.export/isvgoptions/disable_line_end_cropping/) | SVG 1.1 يفتقر إلى القدرة على تعريف الهوامش للعلامات.<br/>            محرك كتابة Aspose.Slides SVG لديه حل بديل لهذه المشكلة:<br/>            يقوم بقص نهاية الخط مع السهم، وبالتالي لا يتقاطع الخط مع العلامات.<br/>            هذا الخيار يعطل هذا السلوك.<br/>            قراءة/كتابة **bool**. |
| [`jpeg_quality`](/slides/python-net/ar/aspose.slides.export/isvgoptions/jpeg_quality/) | يحدد جودة ترميز JPEG.<br/>            قراءة/كتابة **int**. |
| [`shape_formatting_controller`](/slides/python-net/ar/aspose.slides.export/isvgoptions/shape_formatting_controller/) | يعيد ويضبط واجهة رد الاتصال التي تسمح للمستخدم بالتحكم في تحويل الشكل.<br/>            قراءة/كتابة [`ISvgShapeFormattingController`](/slides/python-net/ar/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/ar/aspose.slides.export/isvgoptions/pictures_compression/) | يمثل مستوى ضغط الصور<br/>            قراءة/كتابة [`ISVGOptions.pictures_compression`](/slides/python-net/ar/aspose.slides.export/isvgoptions/pictures_compression). |
| [`delete_pictures_cropped_areas`](/slides/python-net/ar/aspose.slides.export/isvgoptions/delete_pictures_cropped_areas/) | علامة منطقية تشير إلى ما إذا كانت الأجزاء المقتصة تبقى كجزء من المستند. إذا كانت true سيتم حذف الأجزاء المقتصة <br/>            إذا كانت false سيتم تسلسلها في المستند (مما قد يؤدي إلى <br/>            ملف أكبر)<br/>            قراءة/كتابة **bool**. |
| [`use_frame_size`](/slides/python-net/ar/aspose.slides.export/isvgoptions/use_frame_size/) | يحدد ما إذا كان إطار النص سيُدرج في منطقة العرض أم لا.<br/>            قراءة/كتابة **bool**.<br/>            القيمة الافتراضية هي false. |
| [`use_frame_rotation`](/slides/python-net/ar/aspose.slides.export/isvgoptions/use_frame_rotation/) | يحدد ما إذا كان سيتم تنفيذ دوران الشكل المحدد عند العرض أم لا.<br/>            قراءة/كتابة **bool**.<br/>            القيمة الافتراضية هي true. |
| [`external_fonts_handling`](/slides/python-net/ar/aspose.slides.export/isvgoptions/external_fonts_handling/) | يحدد طريقة معالجة الخطوط المحملة من خارج التطبيق.<br/>            قراءة/كتابة [`SvgExternalFontsHandling`](/slides/python-net/ar/aspose.slides.export/svgexternalfontshandling). |
| [`ink_options`](/slides/python-net/ar/aspose.slides.export/isvgoptions/ink_options/) | يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدّر.<br/>            قراءة فقط [`IInkOptions`](/slides/python-net/ar/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/ar/aspose.slides.export/isvgoptions/disable_font_ligatures/) | يعيد أو يضبط قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الروابط الأحرفية.<br/>            عندما يتم تعيينه إلى `true`، سيتم تعطيل الروابط الأحرفية في الناتج المعروض. بشكل افتراضي، يتم تعيين هذه الخاصية إلى `false`. |
| [`warning_callback`](/slides/python-net/ar/aspose.slides.export/isvgoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/ar/aspose.slides.export/isvgoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/ar/aspose.slides.export/isvgoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/ar/aspose.slides.export/isvgoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/ar/aspose.slides.export/isvgoptions/skip_java_script_links/) |  |


### انظر أيضًا
* الوحدة [`aspose.slides.export`](/slides/python-net/ar/aspose.slides.export)
* المكتبة [`Aspose.Slides`](/slides/python-net)