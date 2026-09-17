---
title: PdfOptions class
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.export/pdfoptions/
---
## فئة PdfOptions

يوفر خيارات تتحكم في طريقة حفظ العرض التقديمي بصيغة Pdf.

**الوراثة:**[`PdfOptions`](/slides/python-net/ar/aspose.slides.export/pdfoptions) → [`SaveOptions`](/slides/python-net/ar/aspose.slides.export/saveoptions)

نوع PdfOptions يكشف عن الأعضاء التالية:

## المُنشئات

| المنشئ | الوصف |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ar/aspose.slides.export/pdfoptions/__init__/#) | منشئ افتراضي. |

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`warning_callback`](/slides/python-net/ar/aspose.slides.export/pdfoptions/warning_callback/) | يعيد أو يضبط كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو ستُلغى.<br/>            قراءة/كتابة [`IWarningCallback`](/slides/python-net/ar/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ar/aspose.slides.export/pdfoptions/progress_callback/) | يمثل كائن استدعاء عكسي لتحديث تقدم الحفظ كنسبة مئوية.<br/>            راجع [`IProgressCallback`](/slides/python-net/ar/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ar/aspose.slides.export/pdfoptions/default_regular_font/) | يرجع أو يضبط الخط المستخدم في حالة عدم العثور على الخط المصدر.<br/>            قراءة/كتابة **str**. |
| [`gradient_style`](/slides/python-net/ar/aspose.slides.export/pdfoptions/gradient_style/) | يرجع أو يضبط النمط البصري للتدرج.<br/>            قراءة/كتابة [`GradientStyle`](/slides/python-net/ar/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ar/aspose.slides.export/pdfoptions/skip_java_script_links/) | يحدد ما إذا كان يجب تخطي الروابط التشعبية التي تحتوي على استدعاءات JavaScript عند حفظ العرض التقديمي.<br/>            قراءة/كتابة **bool**. القيمة الافتراضية هي **false**. |
| [`slides_layout_options`](/slides/python-net/ar/aspose.slides.export/pdfoptions/slides_layout_options/) | يحصل أو يضبط الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير العرض التقديمي [`ISlidesLayoutOptions`](/slides/python-net/ar/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/ar/aspose.slides.export/pdfoptions/ink_options/) | يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدَر.<br/>            قراءة فقط [`IInkOptions`](/slides/python-net/ar/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/ar/aspose.slides.export/pdfoptions/show_hidden_slides/) | يحدد ما إذا كان المستند الناتج ينبغي أن يضم الشرائح المخفية أم لا.<br/>            القيمة الافتراضية هي `false`. |
| [`text_compression`](/slides/python-net/ar/aspose.slides.export/pdfoptions/text_compression/) | يحدد نوع الضغط الذي سيُستخدم لجميع المحتويات النصية في المستند.<br/>            قراءة/كتابة [`PdfTextCompression`](/slides/python-net/ar/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/ar/aspose.slides.export/pdfoptions/best_images_compression_ratio/) | يشير إلى ما إذا كان يجب اختيار أكثر ضغط فعّال (بدلاً من الافتراضي) لكل صورة تلقائيًا.<br/>            إذا تم تعيينه إلى **bool**.true، فسيتم اختيار خوارزمية الضغط الأنسب لكل صورة في العرض، مما سيؤدي إلى حجم أصغر للمستند PDF الناتج.<br/>            اختيار أفضل نسبة ضغط للصور مكلف من الناحية الحسابية ويتطلب كمية إضافية من الذاكرة RAM، وهذا الخيار **bool**.false بشكل افتراضي. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/ar/aspose.slides.export/pdfoptions/embed_true_type_fonts_for_ascii/) | يحدد ما إذا كان Aspose.Slides سيضمّن الخطوط الشائعة لنص ASCII (نطاق الأكواد 33..127).<br/>            الخطوط للأكواد التي تتجاوز 127 تُضمّن دائمًا.<br/>            قائمة الخطوط الشائعة تشمل الخطوط الأساسية 14 في PDF وخطوط إضافية يحددها المستخدم.<br/>            قراءة/كتابة **bool**. |
| [`additional_common_font_families`](/slides/python-net/ar/aspose.slides.export/pdfoptions/additional_common_font_families/) | يرجع أو يضبط مصفوفة من أسماء عائلات الخطوط المحددة من قبل المستخدم والتي ينبغي على Aspose.Slides اعتبارها شائعة.<br/>            قراءة/كتابة **str**[]. |
| [`embed_full_fonts`](/slides/python-net/ar/aspose.slides.export/pdfoptions/embed_full_fonts/) | يحدد ما إذا كان يجب تضمين جميع أحرف الخط أو مجرد الجزء المستخدم منه.<br/>            قراءة/كتابة **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/ar/aspose.slides.export/pdfoptions/rasterize_unsupported_font_styles/) | يشير إلى ما إذا كان يجب تحويل النص إلى صورة نقطية (bitmap) وحفظه في PDF عندما لا يدعم الخط نمط الوزن العريض.<br/>            يمكن لهذا الأسلوب تحسين جودة النص في PDF الناتج لبعض الخطوط.<br/>            قراءة/كتابة **bool**. |
| [`jpeg_quality`](/slides/python-net/ar/aspose.slides.export/pdfoptions/jpeg_quality/) | يرجع أو يضبط قيمة تحدد جودة صور JPEG داخل مستند PDF.<br/>            قراءة/كتابة **int**. |
| [`compliance`](/slides/python-net/ar/aspose.slides.export/pdfoptions/compliance/) | مستوى التوافق المطلوب للمستند PDF المُولد.<br/>            قراءة/كتابة [`PdfCompliance`](/slides/python-net/ar/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/ar/aspose.slides.export/pdfoptions/password/) | تعيين كلمة مرور المستخدم لحماية مستند PDF.<br/>            قراءة/كتابة **str**. |
| [`access_permissions`](/slides/python-net/ar/aspose.slides.export/pdfoptions/access_permissions/) | يحتوي على مجموعة من العلامات التي تحدد أي أذونات وصول يجب منحها عند فتح المستند بامتيازات المستخدم.<br/>            راجع [`PdfAccessPermissions`](/slides/python-net/ar/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/ar/aspose.slides.export/pdfoptions/save_metafiles_as_png/) | صحيح لتحويل جميع ملفات الميتا المستخدمة في العرض إلى صور PNG.<br/>            قراءة/كتابة **bool**. |
| [`sufficient_resolution`](/slides/python-net/ar/aspose.slides.export/pdfoptions/sufficient_resolution/) | يرجع أو يضبط قيمة تحدد دقة الصور داخل مستند PDF.<br/>            <br/>الخاصية تؤثر على حجم الملف، وقت التصدير وجودة الصورة.<br/><br/><br/>القيمة الافتراضية هي **96**.<br/><br/><br/>            قراءة/كتابة **float**. |
| [`draw_slides_frame`](/slides/python-net/ar/aspose.slides.export/pdfoptions/draw_slides_frame/) | صحيح لرسم إطار أسود حول كل شريحة.<br/>             قراءة/كتابة **bool**. |
| [`image_transparent_color`](/slides/python-net/ar/aspose.slides.export/pdfoptions/image_transparent_color/) | يحصل أو يضبط لون شفافية الصورة. |
| [`apply_image_transparent`](/slides/python-net/ar/aspose.slides.export/pdfoptions/apply_image_transparent/) | يطبق اللون الشفاف المحدد على الصورة إذا كان `true`. |
| [`include_ole_data`](/slides/python-net/ar/aspose.slides.export/pdfoptions/include_ole_data/) | صحيح لتحويل جميع بيانات OLE من العرض إلى ملفات مضمَّنة في PDF الناتج.<br/>            قراءة/كتابة **bool**. |

### راجع أيضًا
* فئة [`PdfOptions`](/slides/python-net/ar/aspose.slides.export/pdfoptions)
* فئة [`SaveOptions`](/slides/python-net/ar/aspose.slides.export/saveoptions)
* وحدة [`aspose.slides.export`](/slides/python-net/ar/aspose.slides.export)
* مكتبة [`Aspose.Slides`](/slides/python-net)