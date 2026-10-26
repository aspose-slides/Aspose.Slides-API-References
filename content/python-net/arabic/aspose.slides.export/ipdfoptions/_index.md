---
title: IPdfOptions class
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.export/ipdfoptions/
---
## IPdfOptions فئة

يوفر خيارات تتحكم في كيفية حفظ العرض التقديمي بتنسيق Pdf.

نوع IPdfOptions يعرض الأعضاء التالية:

## الخصائص

| خاصية | وصف |
| :- | :- |
| [`text_compression`](/slides/python-net/ar/aspose.slides.export/ipdfoptions/text_compression/) | يحدد نوع الضغط الذي سيُستخدم لجميع المحتويات النصية في المستند.<br/>            قراءة/كتابة [`PdfTextCompression`](/slides/python-net/ar/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/ar/aspose.slides.export/ipdfoptions/best_images_compression_ratio/) | يشير إلى ما إذا كان يجب اختيار أكثر ضغط فعّال (بدلاً من الضبط الافتراضي) لكل صورة تلقائيًا.<br/>            إذا تم تعيينه إلى **bool**.true، سيتم اختيار خوارزمية الضغط الأنسب لكل صورة في العرض التقديمي، مما سيؤدي إلى تقليل حجم مستند PDF الناتج.<br/>            اختيار أفضل نسب ضغط للصور يتطلب حسابات مكثفة ويستهلك كمية إضافية من الذاكرة RAM، وهذا الخيار يكون **bool**.false بشكل افتراضي. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/ar/aspose.slides.export/ipdfoptions/embed_true_type_fonts_for_ascii/) | صحيح لتضمين خطوط true type للأحرف ASCII 32-127.<br/>            الخطوط للأكواد الأحرف التي تتجاوز 127 تُضمّن دائمًا.<br/>            قراءة/كتابة **bool**. |
| [`show_hidden_slides`](/slides/python-net/ar/aspose.slides.export/ipdfoptions/show_hidden_slides/) | يحدد ما إذا كان المستند المُولد يجب أن يشمل الشرائح المخفية أم لا.<br/>            القيمة الافتراضية هي `false`. |
| [`additional_common_font_families`](/slides/python-net/ar/aspose.slides.export/ipdfoptions/additional_common_font_families/) | يعيد أو يضبط مصفوفة من أسماء عائلات الخطوط التي يعرفها المستخدم والتي يجب على Aspose.Slides اعتبارها شائعة.<br/>            قراءة/كتابة **str**[]. |
| [`embed_full_fonts`](/slides/python-net/ar/aspose.slides.export/ipdfoptions/embed_full_fonts/) | يحدد ما إذا كان يجب تضمين جميع أحرف الخط أم فقط الجزء المستخدم.<br/>            قراءة/كتابة **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/ar/aspose.slides.export/ipdfoptions/rasterize_unsupported_font_styles/) | يشير إلى ما إذا كان يجب تحويل النص إلى صورة نقطية (bitmap) وحفظه في PDF عندما لا يدعم الخط تنسيق العريض.<br/>            يمكن لهذا النهج تحسين جودة النص في PDF الناتج لبعض الخطوط.<br/>            قراءة/كتابة **bool**. |
| [`jpeg_quality`](/slides/python-net/ar/aspose.slides.export/ipdfoptions/jpeg_quality/) | يعيد أو يضبط قيمة تحدد جودة صور JPEG داخل مستند PDF.<br/>            قراءة/كتابة **int**. |
| [`compliance`](/slides/python-net/ar/aspose.slides.export/ipdfoptions/compliance/) | مستوى الالتزام المطلوب للمستند PDF المُولد.<br/>            قراءة/كتابة [`PdfCompliance`](/slides/python-net/ar/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/ar/aspose.slides.export/ipdfoptions/password/) | تعيين كلمة مرور المستخدم لحماية مستند PDF.<br/>            قراءة/كتابة **str**. |
| [`access_permissions`](/slides/python-net/ar/aspose.slides.export/ipdfoptions/access_permissions/) | يحتوي على مجموعة من العلامات التي تحدد أي أذونات وصول يجب منحها عندما يُفتح المستند<br/>            باستخدام وصول المستخدم. راجع [`PdfAccessPermissions`](/slides/python-net/ar/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/ar/aspose.slides.export/ipdfoptions/save_metafiles_as_png/) | صحيح لتحويل جميع ملفات الميتا المستخدمة في العرض إلى صور PNG.<br/>            قراءة/كتابة **bool**. |
| [`sufficient_resolution`](/slides/python-net/ar/aspose.slides.export/ipdfoptions/sufficient_resolution/) | يعيد أو يضبط قيمة تحدد دقة الصور داخل مستند PDF.<br/>            <br/>تؤثر الخاصية على حجم الملف، وقت التصدير وجودة الصورة.<br/><br/><br/>القيمة الافتراضية هي **96**.<br/><br/><br/>            قراءة/كتابة **float**. |
| [`draw_slides_frame`](/slides/python-net/ar/aspose.slides.export/ipdfoptions/draw_slides_frame/) | صحيح لرسم إطار أسود حول كل شريحة.<br/>            قراءة/كتابة **bool**. |
| [`slides_layout_options`](/slides/python-net/ar/aspose.slides.export/ipdfoptions/slides_layout_options/) | يحصل أو يضبط الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض [`ISlidesLayoutOptions`](/slides/python-net/ar/aspose.slides.export/islideslayoutoptions). |
| [`image_transparent_color`](/slides/python-net/ar/aspose.slides.export/ipdfoptions/image_transparent_color/) | يحصل أو يضبط اللون الشفاف للصورة. |
| [`apply_image_transparent`](/slides/python-net/ar/aspose.slides.export/ipdfoptions/apply_image_transparent/) | يطبق اللون الشفاف المحدد على صورة إذا كان `true`. |
| [`ink_options`](/slides/python-net/ar/aspose.slides.export/ipdfoptions/ink_options/) | يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدّر.<br/>            قراءة فقط [`IInkOptions`](/slides/python-net/ar/aspose.slides.export/iinkoptions) |
| [`include_ole_data`](/slides/python-net/ar/aspose.slides.export/ipdfoptions/include_ole_data/) | صحيح لتحويل جميع بيانات OLE من العرض إلى ملفات مضمّنة في PDF الناتج.<br/>            قراءة/كتابة **bool**. |
| [`warning_callback`](/slides/python-net/ar/aspose.slides.export/ipdfoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/ar/aspose.slides.export/ipdfoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/ar/aspose.slides.export/ipdfoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/ar/aspose.slides.export/ipdfoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/ar/aspose.slides.export/ipdfoptions/skip_java_script_links/) |  |

### انظر أيضاً
* الوحدة [`aspose.slides.export`](/slides/python-net/ar/aspose.slides.export)
* المكتبة [`Aspose.Slides`](/slides/python-net)