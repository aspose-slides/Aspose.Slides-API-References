---
title: SVGOptions class
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.export/svgoptions/
---
## فئة SVGOptions

يمثل خيارات SVG.

**الوراثة:**[`SVGOptions`](/slides/python-net/ar/aspose.slides.export/svgoptions) → [`SaveOptions`](/slides/python-net/ar/aspose.slides.export/saveoptions)

يُظهر نوع SVGOptions الأعضاء التالية:

## المُنشئات

| المُنشئ | الوصف |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ar/aspose.slides.export/svgoptions/__init__/#) | Initializes a new instance of the SVGOptions class. |
| [`__init__(self, link_embed_controller)`](/slides/python-net/ar/aspose.slides.export/svgoptions/__init__/#ilinkembedcontroller) | Initializes a new instance of the SVGOptions class specifying the link embedding controller object. |

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`warning_callback`](/slides/python-net/ar/aspose.slides.export/svgoptions/warning_callback/) | يرجع أو يعيّن كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو ستُلغى.<br/>            قراءة/كتابة [`IWarningCallback`](/slides/python-net/ar/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ar/aspose.slides.export/svgoptions/progress_callback/) | يمثل كائنًا للنداء الخلفي لتحديثات تقدم الحفظ بالنسبة المئوية.<br/>            راجع [`IProgressCallback`](/slides/python-net/ar/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ar/aspose.slides.export/svgoptions/default_regular_font/) | يرجع أو يعيّن الخط المستخدم في حال عدم العثور على الخط الأصلي.<br/>            قراءة/كتابة **str**. |
| [`gradient_style`](/slides/python-net/ar/aspose.slides.export/svgoptions/gradient_style/) | يرجع أو يعيّن النمط البصري للتدرج.<br/>            قراءة/كتابة [`GradientStyle`](/slides/python-net/ar/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ar/aspose.slides.export/svgoptions/skip_java_script_links/) | يحدد ما إذا كان سيتم تخطي الروابط التشعبية التي تحتوي على استدعاءات جافا سكريبت عند حفظ العرض التقديمي.<br/>            قراءة/كتابة **bool**. القيمة الافتراضية هي **false**. |
| [`ink_options`](/slides/python-net/ar/aspose.slides.export/svgoptions/ink_options/) | يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المصدّر.<br/>            قراءة فقط [`IInkOptions`](/slides/python-net/ar/aspose.slides.export/iinkoptions) |
| [`use_frame_size`](/slides/python-net/ar/aspose.slides.export/svgoptions/use_frame_size/) | يحدد ما إذا كان إطار النص سيُضمن في منطقة العرض أم لا.<br/>            قراءة/كتابة **bool**.<br/>            القيمة الافتراضية هي false. |
| [`use_frame_rotation`](/slides/python-net/ar/aspose.slides.export/svgoptions/use_frame_rotation/) | يحدد ما إذا كان سيتم تنفيذ الدوران المحدد للشكل عند العرض أم لا.<br/>            قراءة/كتابة **bool**.<br/>            القيمة الافتراضية هي true. |
| [`vectorize_text`](/slides/python-net/ar/aspose.slides.export/svgoptions/vectorize_text/) | يحدد ما إذا كان النص على الشريحة سيُحفظ كرسومات.<br/>            قراءة/كتابة **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/ar/aspose.slides.export/svgoptions/metafile_rasterization_dpi/) | يرجع أو يعيّن الحد الأدنى لدقة تحويل ملفات الميتا إلى نقطية.<br/>            قراءة/كتابة **int**. |
| [`disable_3d_text`](/slides/python-net/ar/aspose.slides.export/svgoptions/disable_3d_text/) | يحدد ما إذا كان النص ثلاثي الأبعاد مُعطلًا في SVG.<br/>            قراءة/كتابة **bool**. |
| [`disable_gradient_split`](/slides/python-net/ar/aspose.slides.export/svgoptions/disable_gradient_split/) | يعطل تقسيم التدرجات FromCornerX و FromCenter.<br/>            قراءة/كتابة **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/ar/aspose.slides.export/svgoptions/disable_line_end_cropping/) | تفتقر SVG 1.1 إلى القدرة على تعريف الهوامش للعلامات.<br/>            محرك كتابة Aspose.Slides SVG لديه حل بديل لهذه المشكلة:<br/>            يقص نهاية السطر مع السهم، بحيث لا يتداخل السطر مع العلامات.<br/>            هذا الخيار يوقف هذا السلوك.<br/>            قراءة/كتابة **bool**. |
| [`default`](/slides/python-net/ar/aspose.slides.export/svgoptions/default/) | يرجع الإعدادات الافتراضية.<br/>            قراءة فقط [`SVGOptions`](/slides/python-net/ar/aspose.slides.export/svgoptions). |
| [`simple`](/slides/python-net/ar/aspose.slides.export/svgoptions/simple/) | يرجع إعدادات لتوليد ملف SVG أبسط وأصغر.<br/>            قراءة فقط [`SVGOptions`](/slides/python-net/ar/aspose.slides.export/svgoptions). |
| [`wysiwyg`](/slides/python-net/ar/aspose.slides.export/svgoptions/wysiwyg/) | يرجع إعدادات لتوليد ملف SVG بأعلى دقة.<br/>            قراءة فقط [`SVGOptions`](/slides/python-net/ar/aspose.slides.export/svgoptions). |
| [`jpeg_quality`](/slides/python-net/ar/aspose.slides.export/svgoptions/jpeg_quality/) | يحدد جودة ترميز JPEG.<br/>            قراءة/كتابة **int**. |
| [`shape_formatting_controller`](/slides/python-net/ar/aspose.slides.export/svgoptions/shape_formatting_controller/) | يرجع ويعيّن واجهة استدعاء رد تسمح للمستخدم بالتحكم في تحويل الشكل.<br/>            قراءة/كتابة [`ISvgShapeFormattingController`](/slides/python-net/ar/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/ar/aspose.slides.export/svgoptions/pictures_compression/) | يمثل مستوى ضغط الصور |
| [`delete_pictures_cropped_areas`](/slides/python-net/ar/aspose.slides.export/svgoptions/delete_pictures_cropped_areas/) | علامة منطقية تشير إلى ما إذا كانت الأجزاء المقصوصة ستبقى جزءًا من المستند. إذا كان true سيتم إزالة الأجزاء المقصوصة، إذا كان false سيتم تسلسلها في المستند (مما قد يؤدي إلى ملف أكبر) |
| [`external_fonts_handling`](/slides/python-net/ar/aspose.slides.export/svgoptions/external_fonts_handling/) | يحدد طريقة التعامل مع الخطوط المحمّلة خارجيًا.<br/>            قراءة/كتابة [`SvgExternalFontsHandling`](/slides/python-net/ar/aspose.slides.export/svgexternalfontshandling). |
| [`disable_font_ligatures`](/slides/python-net/ar/aspose.slides.export/svgoptions/disable_font_ligatures/) | يحصل على أو يعيّن قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الحروف المتصلة.<br/>            عندما يُعيّن إلى `true`، سيتم تعطيل الحروف المتصلة في الناتج المعروض. بشكل افتراضي، تُعيّن هذه الخاصية إلى `false`. |


### انظر أيضًا
* الفئة [`SaveOptions`](/slides/python-net/ar/aspose.slides.export/saveoptions)
* الفئة [`SVGOptions`](/slides/python-net/ar/aspose.slides.export/svgoptions)
* الوحدة [`aspose.slides.export`](/slides/python-net/ar/aspose.slides.export)
* المكتبة [`Aspose.Slides`](/slides/python-net)