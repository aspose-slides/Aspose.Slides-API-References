---
title: MarkdownSaveOptions class
second_title: Aspose.Slides للغة Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions فئة

يمثل الخيارات التي تتحكم في كيفية حفظ العرض التقديمي إلى markdown.

**الوراثة:**[`MarkdownSaveOptions`](/slides/python-net/ar/aspose.slides.export/markdownsaveoptions) → [`SaveOptions`](/slides/python-net/ar/aspose.slides.export/saveoptions)

يعرض نوع MarkdownSaveOptions الأعضاء التالية:

## المنشئون

| المنشئ | الوصف |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ar/aspose.slides.export/markdownsaveoptions/__init__/#) | Ctor. |

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`warning_callback`](/slides/python-net/ar/aspose.slides.export/markdownsaveoptions/warning_callback/) | يرجع أو يحدد كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو ستُلغى.<br/>            قراءة/كتابة [`IWarningCallback`](/slides/python-net/ar/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ar/aspose.slides.export/markdownsaveoptions/progress_callback/) | يمثل كائنًا استدعاءً لتحديثات حفظ التقدم كنسبة مئوية.<br/>            راجع [`IProgressCallback`](/slides/python-net/ar/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ar/aspose.slides.export/markdownsaveoptions/default_regular_font/) | يرجع أو يحدد الخط المستخدم في حال عدم العثور على الخط الأصلي.<br/>            قراءة-كتابة **str**. |
| [`gradient_style`](/slides/python-net/ar/aspose.slides.export/markdownsaveoptions/gradient_style/) | يرجع أو يحدد النمط البصري للتدرج.<br/>            قراءة/كتابة [`GradientStyle`](/slides/python-net/ar/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ar/aspose.slides.export/markdownsaveoptions/skip_java_script_links/) | يحدد ما إذا كان يجب تخطي الروابط التشعبية التي تحتوي على استدعاءات JavaScript عند حفظ العرض التقديمي.<br/>            قراءة/كتابة **bool**. القيمة الافتراضية هي **false** . |
| [`export_type`](/slides/python-net/ar/aspose.slides.export/markdownsaveoptions/export_type/) | يحدد مواصفات markdown لتحويل العرض التقديمي.<br/>            القيمة الافتراضية هي `TextOnly`. |
| [`base_path`](/slides/python-net/ar/aspose.slides.export/markdownsaveoptions/base_path/) | يحدد المسار الأساسي حيث سيتم حفظ المستند مع الموارد.<br/>            القيمة الافتراضية هي الدليل الحالي للتطبيق. |
| [`images_save_folder_name`](/slides/python-net/ar/aspose.slides.export/markdownsaveoptions/images_save_folder_name/) | يحدد اسم المجلد لحفظ الصور.<br/>            القيمة الافتراضية هي `Images`. |
| [`new_line_type`](/slides/python-net/ar/aspose.slides.export/markdownsaveoptions/new_line_type/) | يحدد ما إذا كان المستند الناتج يجب أن يحتوي على أسطر جديدة \\r(Macintosh) أو \\n(Unix) أو \\r\\n(Windows).<br/>            القيمة الافتراضية هي `Unix`. |
| [`show_comments`](/slides/python-net/ar/aspose.slides.export/markdownsaveoptions/show_comments/) | يحدد ما إذا كان المستند الناتج يجب أن يظهر التعليقات أم لا.<br/>            القيمة الافتراضية هي `false`. |
| [`show_hidden_slides`](/slides/python-net/ar/aspose.slides.export/markdownsaveoptions/show_hidden_slides/) | يحدد ما إذا كان المستند الناتج يجب أن يتضمن الشرائح المخفية أم لا.<br/>            القيمة الافتراضية هي `false`. |
| [`show_slide_number`](/slides/python-net/ar/aspose.slides.export/markdownsaveoptions/show_slide_number/) | يحدد ما إذا كان المستند الناتج يجب أن يظهر رقم كل شريحة أم لا.<br/>            القيمة الافتراضية هي `false`. |
| [`flavor`](/slides/python-net/ar/aspose.slides.export/markdownsaveoptions/flavor/) | يحدد مواصفات markdown لتحويل العرض التقديمي.<br/>            القيمة الافتراضية هي `Multi-markdown`. |
| [`slide_number_format`](/slides/python-net/ar/aspose.slides.export/markdownsaveoptions/slide_number_format/) | يرجع أو يحدد سلسلة التنسيق المستخدمة لعناوين أرقام الشرائح في إخراج Markdown.<br/>            يجب أن تشمل الصيغة العنصر النائب \"{0}\"، والذي سيُستبدل بترقيم الشريحة أثناء التصدير.<br/>            مثال: \"# Slide {0}\" سينتج \"# Slide 1\", \"# Slide 2\", إلخ. |
| [`handle_repeated_spaces`](/slides/python-net/ar/aspose.slides.export/markdownsaveoptions/handle_repeated_spaces/) |  |
| [`remove_empty_lines`](/slides/python-net/ar/aspose.slides.export/markdownsaveoptions/remove_empty_lines/) | إذا تم تعيينه إلى `true`، يزيل السطور الفارغة أو التي تحتوي فقط على مسافات من الإخراج النهائي للـ Markdown.<br/>            القيمة الافتراضية هي `false`. |

### انظر أيضًا
* فئة [`MarkdownSaveOptions`](/slides/python-net/ar/aspose.slides.export/markdownsaveoptions)
* فئة [`SaveOptions`](/slides/python-net/ar/aspose.slides.export/saveoptions)
* وحدة [`aspose.slides.export`](/slides/python-net/ar/aspose.slides.export)
* مكتبة [`Aspose.Slides`](/slides/python-net)