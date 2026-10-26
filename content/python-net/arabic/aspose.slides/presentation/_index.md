---
title: Presentation class
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/presentation/
---
## فئة Presentation

يمثل عرضًا تقديميًا من Microsoft PowerPoint.

يُظهر نوع Presentation الأعضاء التالية:

## المنشئات

| المنشئ | الوصف |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ar/aspose.slides/presentation/__init__/#) | هذا المنشئ ينشئ عرض تقديمي جديد من الصفر.<br/>            يحتوي العرض التقديمي المنشأ على شريحة واحدة فارغة. |
| [`__init__(self, load_options)`](/slides/python-net/ar/aspose.slides/presentation/__init__/#loadoptions) | هذا المنشئ ينشئ عرض تقديمي جديد من الصفر.<br/>            يحتوي العرض التقديمي المنشأ على شريحة واحدة فارغة. |
| [`__init__(self, stream)`](/slides/python-net/ar/aspose.slides/presentation/__init__/#iorawiobase) | هذا المنشئ هو الآلية الأساسية لقراءة Presentation موجودة. |
| [`__init__(self, stream, load_options)`](/slides/python-net/ar/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | هذا المنشئ هو الآلية الأساسية لقراءة Presentation موجودة. |
| [`__init__(self, file)`](/slides/python-net/ar/aspose.slides/presentation/__init__/#str) | هذا المنشئ يحصل على مسار ملف المصدر الذي تُقرأ منه<br/>             محتويات Presentation. |
| [`__init__(self, file, load_options)`](/slides/python-net/ar/aspose.slides/presentation/__init__/#str-loadoptions) | هذا المنشئ يحصل على مسار ملف المصدر الذي تُقرأ منه<br/>            محتويات Presentation. |

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`current_date_time`](/slides/python-net/ar/aspose.slides/presentation/current_date_time/) | إرجاع أو تعيين التاريخ والوقت اللذين سيستبدلان محتوى حقول datetime.<br/>            وقت إنشاء كائن Presentation هذا بشكل افتراضي.<br/>            قراءة/كتابة **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/ar/aspose.slides/presentation/header_footer_manager/) | إرجاع مدير HeaderFooter الفعلي.<br/>            قراءة فقط [`IPresentationHeaderFooterManager`](/slides/python-net/ar/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/ar/aspose.slides/presentation/protection_manager/) | يحصل على مدير الأذونات لهذا العرض التقديمي.<br/>            قراءة فقط [`IProtectionManager`](/slides/python-net/ar/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/ar/aspose.slides/presentation/slides/) | إرجاع قائمة بجميع الشرائح المعرفة في العرض التقديمي.<br/ar/>            قراءة فقط [`ISlideCollection`](/slides/python-net/ar/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/ar/aspose.slides/presentation/sections/) | إرجاع قائمة بجميع أقسام الشرائح المعرفة في العرض التقديمي.<br/>            قراءة فقط [`ISectionCollection`](/slides/python-net/ar/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/ar/aspose.slides/presentation/slide_size/) | إرجاع كائن حجم الشريحة.<br/>            قراءة فقط [`ISlideSize`](/slides/python-net/ar/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/ar/aspose.slides/presentation/notes_size/) | إرجاع كائن حجم شريحة الملاحظات.<br/>            قراءة فقط [`INotesSize`](/slides/python-net/ar/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/ar/aspose.slides/presentation/layout_slides/) | إرجاع قائمة بجميع شرائح التخطيط المعرفة في العرض التقديمي.<br/>            قراءة فقط [`IGlobalLayoutSlideCollection`](/slides/python-net/ar/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/ar/aspose.slides/presentation/masters/) | إرجاع قائمة بجميع الشرائح الرئيسية المعرفة في العرض التقديمي.<br/>            قراءة فقط [`IMasterSlideCollection`](/slides/python-net/ar/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/ar/aspose.slides/presentation/master_notes_slide_manager/) | إرجاع مدير الملاحظات الرئيسة.<br/>            قراءة فقط [`IMasterNotesSlideManager`](/slides/python-net/ar/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/ar/aspose.slides/presentation/master_handout_slide_manager/) | إرجاع مدير النسخة المطبوعة الرئيسة.<br/>            قراءة فقط [`IMasterHandoutSlideManager`](/slides/python-net/ar/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/ar/aspose.slides/presentation/fonts_manager/) | إرجاع مدير الخطوط.<br/>            قراءة فقط [`IFontsManager`](/slides/python-net/ar/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/ar/aspose.slides/presentation/default_text_style/) | إرجاع نمط النص الافتراضي للأشكال.<br/>            قراءة فقط [`ITextStyle`](/slides/python-net/ar/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/ar/aspose.slides/presentation/comment_authors/) | إرجاع مجموعة مؤلفي التعليقات.<br/>            قراءة فقط [`ICommentAuthorCollection`](/slides/python-net/ar/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/ar/aspose.slides/presentation/document_properties/) | إرجاع كائن DocumentProperties الذي يحتوي على خصائص المستند القياسية والمخصصة.<br/>            قراءة فقط [`IDocumentProperties`](/slides/python-net/ar/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/ar/aspose.slides/presentation/images/) | إرجاع مجموعة كل الصور في العرض التقديمي.<br/>            قراءة فقط [`IImageCollection`](/slides/python-net/ar/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/ar/aspose.slides/presentation/audios/) | إرجاع مجموعة كل ملفات الصوت المضمنة في العرض التقديمي.<br/>            قراءة فقط [`IAudioCollection`](/slides/python-net/ar/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/ar/aspose.slides/presentation/videos/) | إرجاع مجموعة كل ملفات الفيديو المضمنة في العرض التقديمي.<br/>            قراءة فقط [`IVideoCollection`](/slides/python-net/ar/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/ar/aspose.slides/presentation/slide_show_settings/) | إرجاع إعدادات عرض الشرائح للعرض التقديمي. |
| [`digital_signatures`](/slides/python-net/ar/aspose.slides/presentation/digital_signatures/) | إرجاع مجموعة التوقيعات المستخدمة لتوقيع العرض التقديمي.<br/>            قراءة فقط [`IDigitalSignatureCollection`](/slides/python-net/ar/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/ar/aspose.slides/presentation/custom_data/) | إرجاع البيانات المخصصة للعرض التقديمي.<br/>            قراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/ar/aspose.slides/presentation/all_custom_xml_parts/) | إرجاع جميع أجزاء البيانات المخصصة في العرض التقديمي.<br/>            قراءة فقط [`ICustomXmlPart`](/slides/python-net/ar/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/ar/aspose.slides/presentation/vba_project/) | حصول أو تعيين مشروع VBA مع ماكروات العرض التقديمي.<br/>            قراءة/كتابة [`IVbaProject`](/slides/python-net/ar/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/ar/aspose.slides/presentation/hyperlink_queries/) | يوفر وصولًا سهلاً إلى جميع الروابط التشعبية الموجودة في جميع شرائح العرض التقديمي (ليس في الشرائح الرئيسة أو التخطيط أو الملاحظات).<br/>            قراءة فقط [`IHyperlinkQueries`](/slides/python-net/ar/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/ar/aspose.slides/presentation/view_properties/) | يحصل على خصائص العرض الواسعة للعرض التقديمي.<br/>            قراءة فقط [`IViewProperties`](/slides/python-net/ar/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/ar/aspose.slides/presentation/first_slide_number/) | يمثل رقم الشريحة الأولى في العرض التقديمي |
| [`sensitivity_labels`](/slides/python-net/ar/aspose.slides/presentation/sensitivity_labels/) | إرجاع مجموعة علامات الحساسية المطبقة على مستند العرض التقديمي.<br/>            قراءة فقط [`ISensitivityLabelCollection`](/slides/python-net/ar/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/ar/aspose.slides/presentation/source_format/) | إرجاع معلومات حول الصيغة التي تم تحميل العرض التقديمي منها.<br/>            قراءة فقط [`SourceFormat`](/slides/python-net/ar/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/ar/aspose.slides/presentation/master_theme/) | إرجاع السمة الرئيسة.<br/>            قراءة فقط [`IMasterTheme`](/slides/python-net/ar/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/ar/aspose.slides/presentation/presentation/) |  |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/ar/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | يحفظ جميع شرائح العرض التقديمي إلى ملف بالصيغة المحددة. |
| [`save(self, stream, format)`](/slides/python-net/ar/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | يحفظ جميع شرائح العرض التقديمي إلى تدفق بالصيغة المحددة. |
| [`save(self, fname, format, options)`](/slides/python-net/ar/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/ar/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | يحفظ جميع شرائح العرض التقديمي إلى تدفق بالصيغة المحددة ومع خيارات إضافية. |
| [`save(self, options)`](/slides/python-net/ar/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | يحفظ جميع شرائح العرض التقديمي إلى مجموعة من الملفات التي تمثل ترميز XAML. |
| [`save(self, fname, slides, format)`](/slides/python-net/ar/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | يحفظ الشرائح المحددة من العرض التقديمي إلى ملف بالصيغة المحددة مع الحفاظ على أرقام الصفحات. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/ar/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | يحفظ الشرائح المحددة من العرض التقديمي إلى ملف بالصيغة المحددة مع الحفاظ على أرقام الصفحات. |
| [`save(self, stream, slides, format)`](/slides/python-net/ar/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | يحفظ الشرائح المحددة من العرض التقديمي إلى تدفق بالصيغة المحددة مع الحفاظ على أرقام الصفحات. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/ar/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | يحفظ الشرائح المحددة من العرض التقديمي إلى تدفق بالصيغة المحددة مع الحفاظ على أرقام الصفحات. |
| [`get_images(self, options)`](/slides/python-net/ar/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | إرجاع كائنات Image لجميع شرائح العرض التقديمي. |
| [`get_images(self, options, slides)`](/slides/python-net/ar/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | إرجاع كائنات Thumbnail Image للشرائح المحددة من العرض التقديمي. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | إرجاع كائنات Thumbnail Image لجميع شرائح العرض التقديمي مع مقياس مخصص. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | إرجاع كائنات Thumbnail Image للشرائح المحددة من العرض التقديمي مع مقياس مخصص. |
| [`get_images(self, options, image_size)`](/slides/python-net/ar/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | إرجاع كائنات Thumbnail Image لجميع شرائح العرض التقديمي بالحجم المحدد. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/ar/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | إرجاع كائنات Thumbnail Image للشرائح المحددة من العرض التقديمي بالحجم المحدد. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/ar/aspose.slides/presentation/highlight_text/#str-asposeslidescolor) | يبرز جميع التطابقات للنص النموذجي باللون المحدد. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/ar/aspose.slides/presentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | يبرز جميع التطابقات للنص النموذجي باللون المحدد. |
| [`get_slide_by_id(self, id)`](/slides/python-net/ar/aspose.slides/presentation/get_slide_by_id/#int) | إرجاع Slide أو MasterSlide أو LayoutSlide حسب المعرف. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ar/aspose.slides/presentation/join_portions_with_same_formatting/#) | يجمع السلاسل ذات التنسيق المتطابق في جميع الفقرات داخل جميع الأشكال القابلة للقبول في جميع الشرائح. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/ar/aspose.slides/presentation/highlight_regex/#str-asposeslidescolor) | يبرز جميع التطابقات للتعبير النمطي باللون المحدد. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/ar/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | يستبدل جميع تكرارات النص المحدد بنص آخر محدد. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/ar/aspose.slides/presentation/replace_regex/#str-str) | يستبدل جميع التطابقات للتعبير النمطي بالسلسلة المحددة. |

### انظر أيضًا
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)