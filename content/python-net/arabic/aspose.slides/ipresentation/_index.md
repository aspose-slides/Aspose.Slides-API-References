---
title: IPresentation class
second_title: مرجع API لـ Aspose.Slides للـ Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides/ipresentation/
---
## فئة IPresentation

مستند عرض تقديمي

يعرض نوع IPresentation الأعضاء التاليين:

## الخصائص

| خاصية | الوصف |
| :- | :- |
| [`current_date_time`](/slides/python-net/ar/aspose.slides/ipresentation/current_date_time/) | إرجاع أو تعيين التاريخ والوقت الذين سيستبدلان محتوى حقول datetime.<br/>            وقت إنشاء كائن Presentation هذا بشكل افتراضي.<br/>            قراءة/كتابة **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/ar/aspose.slides/ipresentation/header_footer_manager/) | إرجاع مدير HeaderFooter للعرض التقديمي.<br/>            قراءة فقط [`IPresentationHeaderFooterManager`](/slides/python-net/ar/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/ar/aspose.slides/ipresentation/protection_manager/) | الحصول على مدير الأذونات لهذا العرض التقديمي.<br/>            قراءة فقط [`IProtectionManager`](/slides/python-net/ar/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/ar/aspose.slides/ipresentation/slides/) | إرجاع قائمة بجميع الشرائح المعرفة في العرض التقديمي.<br/ar/>            قراءة فقط [`ISlideCollection`](/slides/python-net/ar/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/ar/aspose.slides/ipresentation/sections/) | إرجاع قائمة بجميع أقسام الشرائح المعرفة في العرض التقديمي.<br/>            قراءة فقط [`ISectionCollection`](/slides/python-net/ar/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/ar/aspose.slides/ipresentation/slide_size/) | إرجاع كائن حجم الشريحة.<br/>            قراءة فقط [`ISlideSize`](/slides/python-net/ar/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/ar/aspose.slides/ipresentation/notes_size/) | إرجاع كائن حجم شريحة الملاحظات.<br/>            قراءة فقط [`INotesSize`](/slides/python-net/ar/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/ar/aspose.slides/ipresentation/layout_slides/) | إرجاع قائمة بجميع شرائح التخطيط المعرفة في العرض التقديمي.<br/>            قراءة فقط [`IGlobalLayoutSlideCollection`](/slides/python-net/ar/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/ar/aspose.slides/ipresentation/masters/) | إرجاع قائمة بجميع الشرائح الرئيسة المعرفة في العرض التقديمي.<br/>            قراءة فقط [`IMasterSlideCollection`](/slides/python-net/ar/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/ar/aspose.slides/ipresentation/master_notes_slide_manager/) | إرجاع مدير الملاحظات الرئيسة.<br/>            قراءة فقط [`IMasterNotesSlideManager`](/slides/python-net/ar/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/ar/aspose.slides/ipresentation/master_handout_slide_manager/) | إرجاع مدير النسخة المطبوعة الرئيسة.<br/>            قراءة فقط [`IMasterHandoutSlideManager`](/slides/python-net/ar/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/ar/aspose.slides/ipresentation/fonts_manager/) | إرجاع مدير الخطوط.<br/>            قراءة فقط [`IFontsManager`](/slides/python-net/ar/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/ar/aspose.slides/ipresentation/default_text_style/) | إرجاع نمط النص الافتراضي للأشكال.<br/>            قراءة فقط [`ITextStyle`](/slides/python-net/ar/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/ar/aspose.slides/ipresentation/comment_authors/) | إرجاع مجموعة مؤلفي التعليقات.<br/>            قراءة فقط [`ICommentAuthorCollection`](/slides/python-net/ar/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/ar/aspose.slides/ipresentation/document_properties/) | إرجاع كائن DocumentProperties الذي يحتوي على خصائص المستند القياسية والمخصصة.<br/>            قراءة فقط [`IDocumentProperties`](/slides/python-net/ar/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/ar/aspose.slides/ipresentation/images/) | إرجاع مجموعة جميع الصور في العرض التقديمي.<br/>            قراءة فقط [`IImageCollection`](/slides/python-net/ar/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/ar/aspose.slides/ipresentation/audios/) | إرجاع مجموعة جميع ملفات الصوت المضمنة في العرض التقديمي.<br/>            قراءة فقط [`IAudioCollection`](/slides/python-net/ar/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/ar/aspose.slides/ipresentation/videos/) | إرجاع مجموعة جميع ملفات الفيديو المضمنة في العرض التقديمي.<br/>            قراءة فقط [`IVideoCollection`](/slides/python-net/ar/aspose.slides/ivideocollection). |
| [`custom_data`](/slides/python-net/ar/aspose.slides/ipresentation/custom_data/) | إرجاع البيانات المخصصة للعرض التقديمي.<br/>            قراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`vba_project`](/slides/python-net/ar/aspose.slides/ipresentation/vba_project/) | الحصول على مشروع VBA مع ماكروهات العرض التقديمي.<br/>            قراءة/كتابة [`IVbaProject`](/slides/python-net/ar/aspose.slides.vba/ivbaproject). |
| [`source_format`](/slides/python-net/ar/aspose.slides/ipresentation/source_format/) | إرجاع معلومات حول التنسيق الذي تم تحميل العرض التقديمي منه.<br/>            قراءة فقط [`IPresentation.source_format`](/slides/python-net/ar/aspose.slides/ipresentation/source_format). |
| [`master_theme`](/slides/python-net/ar/aspose.slides/ipresentation/master_theme/) | إرجاع السمة الرئيسة للعرض التقديمي.<br/>            قراءة فقط [`IMasterTheme`](/slides/python-net/ar/aspose.slides.theme/imastertheme). |
| [`hyperlink_queries`](/slides/python-net/ar/aspose.slides/ipresentation/hyperlink_queries/) | يوفر وصولًا سهلاً إلى جميع الروابط التشعبية الموجودة في جميع شرائح العرض التقديمي (باستثناء الشرائح الرئيسة، التخطيط، والملاحظات).<br/>            قراءة فقط [`IHyperlinkQueries`](/slides/python-net/ar/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/ar/aspose.slides/ipresentation/view_properties/) | الحصول على خصائص عرض العرض التقديمي العامة.<br/>            قراءة فقط [`IViewProperties`](/slides/python-net/ar/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/ar/aspose.slides/ipresentation/first_slide_number/) | يمثل رقم الشريحة الأولى في العرض التقديمي.<br/>            قراءة/كتابة **int**. |
| [`all_custom_xml_parts`](/slides/python-net/ar/aspose.slides/ipresentation/all_custom_xml_parts/) | إرجاع جميع أجزاء البيانات المخصصة في العرض التقديمي.<br/>            قراءة فقط [`ICustomXmlPart`](/slides/python-net/ar/aspose.slides/icustomxmlpart)[]. |
| [`digital_signatures`](/slides/python-net/ar/aspose.slides/ipresentation/digital_signatures/) | إرجاع مجموعة التوقيعات المستخدمة لتوقيع العرض التقديمي.<br/>            قراءة فقط [`IDigitalSignatureCollection`](/slides/python-net/ar/aspose.slides/idigitalsignaturecollection). |
| [`sensitivity_labels`](/slides/python-net/ar/aspose.slides/ipresentation/sensitivity_labels/) | إرجاع مجموعة تسميات الحساسية المطبقة على مستند العرض التقديمي.<br/>            قراءة فقط [`ISensitivityLabelCollection`](/slides/python-net/ar/aspose.slides/isensitivitylabelcollection). |
| [`presentation`](/slides/python-net/ar/aspose.slides/ipresentation/presentation/) |  |

## الطرق

| طريقة | الوصف |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/ar/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat) | يحفظ جميع شرائح العرض التقديمي إلى ملف بالتنسيق المحدد. |
| [`save(self, stream, format)`](/slides/python-net/ar/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat) | يحفظ جميع شرائح العرض التقديمي إلى تدفق بالتنسيق المحدد. |
| [`save(self, fname, format, options)`](/slides/python-net/ar/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | يحفظ جميع شرائح العرض التقديمي إلى ملف بالتنسيق المحدد ومع خيارات إضافية. |
| [`save(self, stream, format, options)`](/slides/python-net/ar/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | يحفظ جميع شرائح العرض التقديمي إلى تدفق بالتنسيق المحدد ومع خيارات إضافية. |
| [`save(self, fname, slides, format)`](/slides/python-net/ar/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat) | يحفظ الشرائح المحددة من العرض التقديمي إلى ملف بالتنسيق المحدد. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/ar/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | يحفظ الشرائح المحددة من العرض التقديمي إلى ملف بالتنسيق المحدد. |
| [`save(self, stream, slides, format)`](/slides/python-net/ar/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | يحفظ الشرائح المحددة من العرض التقديمي إلى تدفق بالتنسيق المحدد. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/ar/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | يحفظ الشرائح المحددة من العرض التقديمي إلى تدفق بالتنسيق المحدد. |
| [`save(self, options)`](/slides/python-net/ar/aspose.slides/ipresentation/save/#asposeslidesexportxamlixamloptions) | يحفظ جميع شرائح العرض التقديمي إلى مجموعة من الملفات التي تمثل ترميز XAML. |
| [`get_images(self, options)`](/slides/python-net/ar/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions) | إرجاع كائنات صورة المصغرات لجميع شرائح العرض التقديمي. |
| [`get_images(self, options, slides)`](/slides/python-net/ar/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint) | إرجاع كائنات بيت ماب المصغرة للشرائح المحددة من العرض التقديمي. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-float-float) | إرجاع كائنات صورة المصغرات لجميع شرائح العرض التقديمي مع قياس مخصص. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | إرجاع كائنات صورة المصغرات للشرائح المحددة من العرض التقديمي مع قياس مخصص. |
| [`get_images(self, options, image_size)`](/slides/python-net/ar/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-asposepydrawingsize) | إرجاع كائنات صورة المصغرات لجميع شرائح العرض التقديمي بالحجم المحدد. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/ar/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-asposepydrawingsize) | إرجاع كائنات صورة المصغرات للشرائح المحددة من العرض التقديمي بالحجم المحدد. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/ar/aspose.slides/ipresentation/highlight_text/#str-asposepydrawingcolor) | تمييز جميع التطابقات للنص العيني باللون المحدد. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/ar/aspose.slides/ipresentation/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | تمييز جميع التطابقات للنص العيني باللون المحدد. |
| [`get_slide_by_id(self, id)`](/slides/python-net/ar/aspose.slides/ipresentation/get_slide_by_id/#int) | إرجاع شريحة Slide أو MasterSlide أو LayoutSlide حسب المعرف. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ar/aspose.slides/ipresentation/join_portions_with_same_formatting/#) | دمج المقاطع ذات التنسيق المتطابق في جميع الفقرات داخل جميع الأشكال المقبولة في جميع الشرائح. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/ar/aspose.slides/ipresentation/highlight_regex/#str-asposepydrawingcolor) | تمييز جميع التطابقات للتعبير النمطي باللون المحدد. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/ar/aspose.slides/ipresentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | استبدال جميع حالات النص المحدد بنص محدد آخر. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/ar/aspose.slides/ipresentation/replace_regex/#str-str) | استبدال جميع التطابقات للتعبير النمطي بالسلسلة المحددة. |

### انظر أيضًا
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)