---
title: HtmlOptions class
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.export/htmloptions/
---
## HtmlOptions فئة

يمثل خيارات تصدير HTML.

**Inheritance:**[`HtmlOptions`](/slides/python-net/ar/aspose.slides.export/htmloptions) → [`SaveOptions`](/slides/python-net/ar/aspose.slides.export/saveoptions)

نوع HtmlOptions يُظهر الأعضاء التالية:

## المنشئات

| Constructor | Description |
| :- | :- |
| [`__init__(self, link_embed_controller)`](/slides/python-net/ar/aspose.slides.export/htmloptions/__init__/#ilinkembedcontroller) | Creates a new HtmlOptions object specifiing callback. |
| [`__init__(self)`](/slides/python-net/ar/aspose.slides.export/htmloptions/__init__/#) | Creates a new HtmlOptions object for saving into single HTML file. |

## الخصائص

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/ar/aspose.slides.export/htmloptions/warning_callback/) | إرجاع أو تعيين كائن يتلقى التحذيرات ويقرر ما إذا كان عملية التحميل ستستمر أو سيتم إلغاؤها.<br/>            قراءة/كتابة [`IWarningCallback`](/slides/python-net/ar/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ar/aspose.slides.export/htmloptions/progress_callback/) | يمثل كائنًا لاستدعاء يتم استخدامه لتحديثات تقدم الحفظ بالنسبة المئوية.<br/>            انظر [`IProgressCallback`](/slides/python-net/ar/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ar/aspose.slides.export/htmloptions/default_regular_font/) | إرجاع أو تعيين الخط المستخدم في حال عدم العثور على الخط المصدر.<br/>            قراءة/كتابة **str**. |
| [`gradient_style`](/slides/python-net/ar/aspose.slides.export/htmloptions/gradient_style/) | إرجاع أو تعيين النمط البصري للتدرج.<br/>            قراءة/كتابة [`GradientStyle`](/slides/python-net/ar/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ar/aspose.slides.export/htmloptions/skip_java_script_links/) | يحدد ما إذا كان يجب تخطي الروابط التشعبية التي تحتوي على استدعاءات JavaScript عند حفظ العرض التقديمي. <br/>            قراءة/كتابة **bool**. القيمة الافتراضية هي **false**. |
| [`slides_layout_options`](/slides/python-net/ar/aspose.slides.export/htmloptions/slides_layout_options/) | إرجاع أو تعيين الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [`ISlidesLayoutOptions`](/slides/python-net/ar/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/ar/aspose.slides.export/htmloptions/ink_options/) | يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدَّر.<br/>            قراءة فقط [`IInkOptions`](/slides/python-net/ar/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/ar/aspose.slides.export/htmloptions/show_hidden_slides/) | يحدد ما إذا كان المستند المُولَّد يجب أن يضم الشرائح المخفية أم لا.<br/>            القيمة الافتراضية هي `false`. |
| [`html_formatter`](/slides/python-net/ar/aspose.slides.export/htmloptions/html_formatter/) | إرجاع أو تعيين قالب HTML.<br/>            قراءة/كتابة [`IHtmlFormatter`](/slides/python-net/ar/aspose.slides.export/ihtmlformatter). |
| [`disable_font_ligatures`](/slides/python-net/ar/aspose.slides.export/htmloptions/disable_font_ligatures/) | إرجاع أو تعيين قيمة تشير إلى ما إذا تم عرض النص دون استخدام الحروف المتصلة.<br/>            عند تعيينها إلى `true`، سيتم تعطيل الحروف المتصلة في النتيجة المعروضة. بشكل افتراضي، تُضبط هذه الخاصية على `false`. |
| [`slide_image_format`](/slides/python-net/ar/aspose.slides.export/htmloptions/slide_image_format/) | إرجاع أو تعيين خيارات تنسيق صور الشرائح.<br/>            قراءة/كتابة [`ISlideImageFormat`](/slides/python-net/ar/aspose.slides.export/islideimageformat). |
| [`jpeg_quality`](/slides/python-net/ar/aspose.slides.export/htmloptions/jpeg_quality/) | إرجاع أو تعيين قيمة تحدد جودة صور JPEG داخل مستند PDF.<br/>            قراءة/كتابة **int**. |
| [`pictures_compression`](/slides/python-net/ar/aspose.slides.export/htmloptions/pictures_compression/) | يمثل مستوى ضغط الصور |
| [`delete_pictures_cropped_areas`](/slides/python-net/ar/aspose.slides.export/htmloptions/delete_pictures_cropped_areas/) | علامة منطقية تشير إلى ما إذا كانت الأجزاء المقصوصة ستبقى جزءًا من المستند. إذا كانت true ستُزال الأجزاء المقصوصة، وإذا كانت false ستتم تسلسلها في المستند (مما قد يؤدي إلى ملف أكبر) |
| [`svg_responsive_layout`](/slides/python-net/ar/aspose.slides.export/htmloptions/svg_responsive_layout/) | True لاستبعاد سمات العرض والارتفاع من حاوية svg - سيجعل ذلك التخطيط مستجيبًا. False - خلاف ذلك.<br/>            قراءة/كتابة **bool**. |

### انظر أيضًا
* فئة [`HtmlOptions`](/slides/python-net/ar/aspose.slides.export/htmloptions)
* فئة [`SaveOptions`](/slides/python-net/ar/aspose.slides.export/saveoptions)
* وحدة [`aspose.slides.export`](/slides/python-net/ar/aspose.slides.export)
* مكتبة [`Aspose.Slides`](/slides/python-net)