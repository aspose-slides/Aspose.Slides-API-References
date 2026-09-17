---
title: SwfOptions class
second_title: مرجع API لـ Aspose.Slides للـ Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides.export/swfoptions/
---
## فئة SwfOptions

توفر خيارات تتحكم في كيفية حفظ العرض التقديمي بصيغة Swf.

**الوراثة:**[`SwfOptions`](/slides/python-net/ar/aspose.slides.export/swfoptions) → [`SaveOptions`](/slides/python-net/ar/aspose.slides.export/saveoptions)

يوضح نوع SwfOptions الأعضاء التالية:

## المنشئات

| المنشئ | الوصف |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ar/aspose.slides.export/swfoptions/__init__/#) | المنشئ الافتراضي. |

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`warning_callback`](/slides/python-net/ar/aspose.slides.export/swfoptions/warning_callback/) | يعيد أو يعيّن كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو ستُوقف.<br/>            قراءة/كتابة [`IWarningCallback`](/slides/python-net/ar/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ar/aspose.slides.export/swfoptions/progress_callback/) | يمثل كائنًا استدعاءً للرد يعرض تحديثات تقدم الحفظ بالنسبة المئوية.<br/>            راجع [`IProgressCallback`](/slides/python-net/ar/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ar/aspose.slides.export/swfoptions/default_regular_font/) | يعيد أو يعيّن الخط المستخدم في حال عدم العثور على الخط المصدر.<br/>            قراءة/كتابة **str**. |
| [`gradient_style`](/slides/python-net/ar/aspose.slides.export/swfoptions/gradient_style/) | يعيد أو يعيّن النمط البصري للتدرج.<br/>            قراءة/كتابة [`GradientStyle`](/slides/python-net/ar/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ar/aspose.slides.export/swfoptions/skip_java_script_links/) | يحدد ما إذا كان يجب تخطي الروابط ذات استدعاءات JavaScript عند حفظ العرض التقديمي.<br/>            قراءة/كتابة **bool**. القيمة الافتراضية هي **false**. |
| [`show_hidden_slides`](/slides/python-net/ar/aspose.slides.export/swfoptions/show_hidden_slides/) | يحدد ما إذا كان المستند المُولد يجب أن يتضمن الشرائح المخفية أم لا.<br/>            القيمة الافتراضية هي `false`. |
| [`compressed`](/slides/python-net/ar/aspose.slides.export/swfoptions/compressed/) | يحدد ما إذا كان المستند SWF المُولد يجب أن يُضغط أم لا.<br/>            القيمة الافتراضية هي `true`. |
| [`viewer_included`](/slides/python-net/ar/aspose.slides.export/swfoptions/viewer_included/) | يحدد ما إذا كان المستند SWF المُولد يجب أن يتضمن عارض المستند المتكامل أم لا.<br/>            القيمة الافتراضية هي `true`. |
| [`show_page_border`](/slides/python-net/ar/aspose.slides.export/swfoptions/show_page_border/) | يحدد ما إذا كان يجب إظهار الحدود حول الصفحات. القيمة الافتراضية هي true. |
| [`show_full_screen`](/slides/python-net/ar/aspose.slides.export/swfoptions/show_full_screen/) | إظهار/إخفاء زر ملء الشاشة. يمكن تجاوز ذلك في flashvars. القيمة الافتراضية هي true. |
| [`show_page_stepper`](/slides/python-net/ar/aspose.slides.export/swfoptions/show_page_stepper/) | إظهار/إخفاء متحكم الصفحات. يمكن تجاوز ذلك في flashvars. القيمة الافتراضية هي true. |
| [`show_search`](/slides/python-net/ar/aspose.slides.export/swfoptions/show_search/) | إظهار/إخفاء قسم البحث. يمكن تجاوز ذلك في flashvars. القيمة الافتراضية هي true. |
| [`show_top_pane`](/slides/python-net/ar/aspose.slides.export/swfoptions/show_top_pane/) | إظهار/إخفاء اللوحة العلوية بالكامل. يمكن تجاوز ذلك في flashvars. القيمة الافتراضية هي true. |
| [`show_bottom_pane`](/slides/python-net/ar/aspose.slides.export/swfoptions/show_bottom_pane/) | إظهار/إخفاء اللوحة السفلية. يمكن تجاوز ذلك في flashvars. القيمة الافتراضية هي true. |
| [`show_left_pane`](/slides/python-net/ar/aspose.slides.export/swfoptions/show_left_pane/) | إظهار/إخفاء اللوحة اليسرى. يمكن تجاوز ذلك في flashvars. القيمة الافتراضية هي true. |
| [`start_open_left_pane`](/slides/python-net/ar/aspose.slides.export/swfoptions/start_open_left_pane/) | ابدأ باللوحة اليسرى مفتوحة. يمكن تجاوز ذلك في flashvars. القيمة الافتراضية هي false. |
| [`enable_context_menu`](/slides/python-net/ar/aspose.slides.export/swfoptions/enable_context_menu/) | تمكين/تعطيل قائمة السياق. القيمة الافتراضية هي true. |
| [`logo_image_bytes`](/slides/python-net/ar/aspose.slides.export/swfoptions/logo_image_bytes/) | الصورة التي ستُعرض كشعار في الزاوية اليمنى العليا للعارض.<br/>            يجب أن تكون الصورة PNG بدقة 32x64 بكسل، وإلا قد يُعرض الشعار بشكل غير صحيح. |
| [`logo_link`](/slides/python-net/ar/aspose.slides.export/swfoptions/logo_link/) | يعيد أو يعيّن عنوان الرابط الكامل للشعار.<br/>            له تأثير فقط إذا تم تحديد [`SwfOptions.logo_image_bytes`](/slides/python-net/ar/aspose.slides.export/swfoptions/logo_image_bytes). |
| [`jpeg_quality`](/slides/python-net/ar/aspose.slides.export/swfoptions/jpeg_quality/) | يحدد جودة صور JPEG.<br/>            القيمة الافتراضية هي 95. |
| [`slides_layout_options`](/slides/python-net/ar/aspose.slides.export/swfoptions/slides_layout_options/) | يعيد أو يعيّن الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [`ISlidesLayoutOptions`](/slides/python-net/ar/aspose.slides.export/islideslayoutoptions).<br/>            هذه الخاصية لا تدعم تعيين كائنات من النوع [`HandoutLayoutingOptions`](/slides/python-net/ar/aspose.slides.export/handoutlayoutingoptions). |

### انظر أيضًا
* فئة [`SaveOptions`](/slides/python-net/ar/aspose.slides.export/saveoptions)
* فئة [`SwfOptions`](/slides/python-net/ar/aspose.slides.export/swfoptions)
* وحدة [`aspose.slides.export`](/slides/python-net/ar/aspose.slides.export)
* مكتبة [`Aspose.Slides`](/slides/python-net)