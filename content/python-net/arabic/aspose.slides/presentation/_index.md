---
title: Presentation class
second_title: مرجع API لـ Aspose.Slides للغة Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides/presentation/
---
## الصنف Presentation

يمثّل عرض Microsoft PowerPoint.

يعرض النوع Presentation الأعضاء التالية:

## المنشئات

| المنشئ | الوصف |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ar/aspose.slides/presentation/__init__/#) | هذا المنشئ ينشئ عرض تقديمي جديد من الصفر.<br/>            يحتوي العرض التقديمي المنشأ على شريحة فارغة واحدة. |
| [`__init__(self, load_options)`](/slides/python-net/ar/aspose.slides/presentation/__init__/#loadoptions) | هذا المنشئ ينشئ عرض تقديمي جديد من الصفر.<br/>            يحتوي العرض التقديمي المنشأ على شريحة فارغة واحدة. |
| [`__init__(self, stream)`](/slides/python-net/ar/aspose.slides/presentation/__init__/#iorawiobase) | هذا المنشئ هو الآلية الأساسية لقراءة عرض Presentation موجود. |
| [`__init__(self, stream, load_options)`](/slides/python-net/ar/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | هذا المنشئ هو الآلية الأساسية لقراءة عرض Presentation موجود. |
| [`__init__(self, file)`](/slides/python-net/ar/aspose.slides/presentation/__init__/#str) | هذا المنشئ يحصل على مسار ملف المصدر الذي تُقرأ منه<br/>             محتويات الـPresentation. |
| [`__init__(self, file, load_options)`](/slides/python-net/ar/aspose.slides/presentation/__init__/#str-loadoptions) | هذا المنشئ يحصل على مسار ملف المصدر الذي تُقرأ منه<br/>            محتويات الـPresentation. |

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`current_date_time`](/slides/python-net/ar/aspose.slides/presentation/current_date_time/) | يُرجع أو يعيّن التاريخ والوقت اللذان سيستبدلان محتوى حقول datetime.<br/>            وقت إنشاء كائن Presentation هذا افتراضيًا.<br/>            قراءة/كتابة **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/ar/aspose.slides/presentation/header_footer_manager/) | يُرجع مدير HeaderFooter الفعلي.<br/>            للقراءة فقط [`IPresentationHeaderFooterManager`](/slides/python-net/ar/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/ar/aspose.slides/presentation/protection_manager/) | يحصل على مدير أذونات هذا العرض التقديمي.<br/>            للقراءة فقط [`IProtectionManager`](/slides/python-net/ar/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/ar/aspose.slides/presentation/slides/) | يُرجع قائمة بجميع الشرائح المعرفة في العرض التقديمي.<br/ar/>            للقراءة فقط [`ISlideCollection`](/slides/python-net/ar/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/ar/aspose.slides/presentation/sections/) | يُرجع قائمة بجميع أقسام الشرائح المعرفة في العرض التقديمي.<br/>            للقراءة فقط [`ISectionCollection`](/slides/python-net/ar/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/ar/aspose.slides/presentation/slide_size/) | يُرجع كائن حجم الشريحة.<br/>            للقراءة فقط [`ISlideSize`](/slides/python-net/ar/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/ar/aspose.slides/presentation/notes_size/) | يُرجع كائن حجم شريحة الملاحظات.<br/>            للقراءة فقط [`INotesSize`](/slides/python-net/ar/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/ar/aspose.slides/presentation/layout_slides/) | يُرجع قائمة بجميع شرائح التخطيط المعرفة في العرض التقديمي.<br/>            للقراءة فقط [`IGlobalLayoutSlideCollection`](/slides/python-net/ar/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/ar/aspose.slides/presentation/masters/) | يُرجع قائمة بجميع شرائح الرئيسة المعرفة في العرض التقديمي.<br/>            للقراءة فقط [`IMasterSlideCollection`](/slides/python-net/ar/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/ar/aspose.slides/presentation/master_notes_slide_manager/) | يُرجع مدير ملاحظات الرئيس.<br/>            للقراءة فقط [`IMasterNotesSlideManager`](/slides/python-net/ar/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/ar/aspose.slides/presentation/master_handout_slide_manager/) | يُرجع مدير نسخة الإلقاء الرئيسة.<br/>            للقراءة فقط [`IMasterHandoutSlideManager`](/slides/python-net/ar/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/ar/aspose.slides/presentation/fonts_manager/) | يُرجع مدير الخطوط.<br/>            للقراءة فقط [`IFontsManager`](/slides/python-net/ar/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/ar/aspose.slides/presentation/default_text_style/) | يُرجع نمط النص الافتراضي للأشكال.<br/>            للقراءة فقط [`ITextStyle`](/slides/python-net/ar/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/ar/aspose.slides/presentation/comment_authors/) | يُرجع مجموعة مؤلفي التعليقات.<br/>            للقراءة فقط [`ICommentAuthorCollection`](/slides/python-net/ar/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/ar/aspose.slides/presentation/document_properties/) | يُرجع كائن DocumentProperties الذي يحتوي على خصائص المستند القياسية والمخصصة.<br/>            للقراءة فقط [`IDocumentProperties`](/slides/python-net/ar/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/ar/aspose.slides/presentation/images/) | يُرجع مجموعة جميع الصور في العرض التقديمي.<br/>            للقراءة فقط [`IImageCollection`](/slides/python-net/ar/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/ar/aspose.slides/presentation/audios/) | يُرجع مجموعة جميع ملفات الصوت المدمجة في العرض التقديمي.<br/>            للقراءة فقط [`IAudioCollection`](/slides/python-net/ar/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/ar/aspose.slides/presentation/videos/) | يُرجع مجموعة جميع ملفات الفيديو المدمجة في العرض التقديمي.<br/>            للقراءة فقط [`IVideoCollection`](/slides/python-net/ar/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/ar/aspose.slides/presentation/slide_show_settings/) | يُرجع إعدادات عرض الشرائح للعرض التقديمي. |
| [`digital_signatures`](/slides/python-net/ar/aspose.slides/presentation/digital_signatures/) | يُرجع مجموعة التوقيعات المستخدمة لتوقيع العرض التقديمي.<br/>            للقراءة فقط [`IDigitalSignatureCollection`](/slides/python-net/ar/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/ar/aspose.slides/presentation/custom_data/) | يُرجع البيانات المخصصة للعرض التقديمي.<br/>            للقراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/ar/aspose.slides/presentation/all_custom_xml_parts/) | يُرجع جميع أجزاء البيانات المخصصة في العرض التقديمي.<br/>            للقراءة فقط [`ICustomXmlPart`](/slides/python-net/ar/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/ar/aspose.slides/presentation/vba_project/) | يحصل أو يعيّن مشروع VBA مع الماكروهات الخاصة بالعرض التقديمي.<br/>            قراءة/كتابة [`IVbaProject`](/slides/python-net/ar/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/ar/aspose.slides/presentation/hyperlink_queries/) | يوفر وصولًا سهلاً إلى جميع الارتباطات التشعبية الموجودة في جميع شرائح العرض التقديمي (ليس في الشرائح الرئيسة، التخطيطية، أو ملاحظات الشرائح).<br/>            للقراءة فقط [`IHyperlinkQueries`](/slides/python-net/ar/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/ar/aspose.slides/presentation/view_properties/) | يحصل على خصائص العرض الواسعة للعرض التقديمي.<br/>            للقراءة فقط [`IViewProperties`](/slides/python-net/ar/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/ar/aspose.slides/presentation/first_slide_number/) | يمثّل رقم الشريحة الأولى في العرض التقديمي |
| [`sensitivity_labels`](/slides/python-net/ar/aspose.slides/presentation/sensitivity_labels/) | يُرجع مجموعة تصنيفات الحساسية المطبقة على مستند العرض التقديمي.<br/>            للقراءة فقط [`ISensitivityLabelCollection`](/slides/python-net/ar/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/ar/aspose.slides/presentation/source_format/) | يُرجع معلومات عن الصيغة التي تم تحميل العرض التقديمي منها.<br/>            للقراءة فقط [`SourceFormat`](/slides/python-net/ar/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/ar/aspose.slides/presentation/master_theme/) | يُرجع سمة الرئيس.<br/>            للقراءة فقط [`IMasterTheme`](/slides/python-net/ar/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/ar/aspose.slides/presentation/presentation/) |  |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/ar/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | يحفظ جميع شرائح عرض تقديمي إلى ملف بالتنسيق المحدد. |
| [`save(self, stream, format)`](/slides/python-net/ar/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | يحفظ جميع شرائح عرض تقديمي إلى تيار بالتنسيق المحدد. |
| [`save(self, fname, format, options)`](/slides/python-net/ar/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/ar/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | يحفظ جميع شرائح عرض تقديمي إلى تيار بالتنسيق المحدد ومع خيارات إضافية. |
| [`save(self, options)`](/slides/python-net/ar/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | يحفظ جميع شرائح عرض تقديمي إلى مجموعة من الملفات التي تمثل ترميز XAML. |
| [`save(self, fname, slides, format)`](/slides/python-net/ar/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | يحفظ الشرائح المحددة من عرض تقديمي إلى ملف بالتنسيق المحدد مع الحفاظ على رقم الصفحة. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/ar/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | يحفظ الشرائح المحددة من عرض تقديمي إلى ملف بالتنسيق المحدد مع الحفاظ على رقم الصفحة. |
| [`save(self, stream, slides, format)`](/slides/python-net/ar/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | يحفظ الشرائح المحددة من عرض تقديمي إلى تيار بالتنسيق المحدد مع الحفاظ على رقم الصفحة. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/ar/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | يحفظ الشرائح المحددة من عرض تقديمي إلى تيار بالتنسيق المحدد مع الحفاظ على رقم الصفحة. |
| [`get_images(self, options)`](/slides/python-net/ar/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | يُرجع كائنات Image لجميع شرائح عرض تقديمي. |
| [`get_images(self, options, slides)`](/slides/python-net/ar/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | يُرجع كائنات Thumbnail Image للشرائح المحددة في عرض تقديمي. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | يُرجع كائنات Thumbnail Image لجميع شرائح عرض تقديمي مع تحجيم مخصص. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | يُرجع كائنات Thumbnail Image للشرائح المحددة في عرض تقديمي مع تحجيم مخصص. |
| [`get_images(self, options, image_size)`](/slides/python-net/ar/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | يُرجع كائنات Thumbnail Image لجميع شرائح عرض تقديمي بالحجم المحدد. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/ar/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | يُرجع كائنات Thumbnail Image للشرائح المحددة في عرض تقديمي بالحجم المحدد. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/ar/aspose.slides/presentation/highlight_text/#str-asposeslidescolor) | يبرز جميع تطابقات النص العيني باللون المحدد. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/ar/aspose.slides/presentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | يبرز جميع تطابقات النص العيني باللون المحدد. |
| [`get_slide_by_id(self, id)`](/slides/python-net/ar/aspose.slides/presentation/get_slide_by_id/#int) | يُرجع Slide أو MasterSlide أو LayoutSlide حسب المعرف. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ar/aspose.slides/presentation/join_portions_with_same_formatting/#) | يجمع المقاطع ذات التنسيق المتطابق في جميع الفقرات داخل جميع الأشكال المقبولة في جميع الشرائح. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/ar/aspose.slides/presentation/highlight_regex/#str-asposeslidescolor) | يبرز جميع تطابقات التعبير النمطي باللون المحدد. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/ar/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | يستبدل جميع مرات ظهور النص المحدد بنص آخر محدد. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/ar/aspose.slides/presentation/replace_regex/#str-str) | يستبدل جميع تطابقات التعبير النمطي بالسلسلة المحددة. |
| [`refresh_charts_data(self, skip_failed_charts)`](/slides/python-net/ar/aspose.slides/presentation/refresh_charts_data/#bool) | يعيد تحميل البيانات لجميع المخططات في العرض التقديمي من دفاتر العمل المصدرية الخاصة بها. |

### انظر أيضًا
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)