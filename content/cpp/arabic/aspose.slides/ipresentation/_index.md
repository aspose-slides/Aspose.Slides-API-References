---
title: IPresentation
second_title: مرجع API Aspose.Slides للغة C++
description: مستند العرض التقديمي
type: docs
weight: 3368
url: /ar/aspose.slides/ipresentation/
---
## IPresentation الفئة

[Presentation](../presentation/) مستند

```cpp
class IPresentation : public Aspose::Slides::IPresentationComponent,
                      public System::IDisposable
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual void [Dispose](../../system/idisposable/dispose/)() | لا يفعل شيئًا. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر قيمتا NaN متساويتين بالرغم من أنه وفقًا لـ IEC 60559:1989 فإن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر قيمتا NaN متساويتين بالرغم من أنه وفقًا لـ IEC 60559:1989 فإن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ICustomXmlPart](../icustomxmlpart/)\>\> [get_AllCustomXmlParts](./get_allcustomxmlparts/)() | يعيد جميع أجزاء البيانات المخصصة في العرض التقديمي. للقراءة فقط [ICustomXmlPart](../icustomxmlpart/)[]. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Audio](./get_audio/)(**int32_t**) | يعيد ملف الصوت المضمّن في العرض التقديمي عند الفهرس المحدد. للقراءة فقط [Aspose::Slides::IAudio](../iaudio/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudioCollection](../iaudiocollection/)\> [get_Audios](./get_audios/)() | يعيد مجموعة جميع ملفات الصوت المضمّنة في العرض التقديمي. للقراءة فقط [IAudioCollection](../iaudiocollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\> [get_CommentAuthor](./get_commentauthor/)(**int32_t**) | يعيد مؤلف التعليق عند الفهرس المحدد. للقراءة فقط [Aspose::Slides::ICommentAuthor](../icommentauthor/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthorCollection](../icommentauthorcollection/)\> [get_CommentAuthors](./get_commentauthors/)() | يعيد مجموعة مؤلفي التعليقات. للقراءة فقط [ICommentAuthorCollection](../icommentauthorcollection/). |
| virtual [System::DateTime](../../system/datetime/) [get_CurrentDateTime](./get_currentdatetime/)() | يعيد التاريخ والوقت اللذان سيستبدلان محتوى حقول datetime. وقت إنشاء كائن [Presentation](../presentation/) هذا هو الافتراضي. للقراءة [System::DateTime](../../system/datetime/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() | يعيد البيانات المخصّصة للعرض التقديمي. للقراءة فقط [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_DefaultTextStyle](./get_defaulttextstyle/)() | يعيد نمط النص الافتراضي للأشكال. للقراءة فقط [ITextStyle](../itextstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDigitalSignature](../idigitalsignature/)\> [get_DigitalSignature](./get_digitalsignature/)(**int32_t**) | يعيد التوقيع الرقمي المستخدم لتوقيع العرض التقديمي عند الفهرس المحدد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDigitalSignatureCollection](../idigitalsignaturecollection/)\> [get_DigitalSignatures](./get_digitalsignatures/)() | يعيد مجموعة التوقيعات المستخدمة لتوقيع العرض التقديمي. للقراءة فقط [IDigitalSignatureCollection](../idigitalsignaturecollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [get_DocumentProperties](./get_documentproperties/)() | يعيد كائن [DocumentProperties](../documentproperties/) الذي يحتوي على خصائص المستند القياسية والمخصّصة. للقراءة فقط [IDocumentProperties](../idocumentproperties/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_DocumentProperty](./get_documentproperty/)([System::String](../../system/string/)) | يعيد الخاصية المخصّصة المعرفة بالاسم. |
| virtual **int32_t** [get_FirstSlideNumber](./get_firstslidenumber/)() | يمثل رقم الشريحة الأولى في العرض التقديمي. للقراءة **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontsManager](../ifontsmanager/)\> [get_FontsManager](./get_fontsmanager/)() | يعيد مدير الخطوط. للقراءة فقط [IFontsManager](../ifontsmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentationHeaderFooterManager](../ipresentationheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() | يعيد مدير رأس وتذييل العرض التقديمي. للقراءة فقط [IPresentationHeaderFooterManager](../ipresentationheaderfootermanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](./get_hyperlinkqueries/)() | يوفر وصولًا سهلاً إلى جميع الروابط التشعبية الموجودة في جميع شرائح العرض التقديمي (ليس في القالب، التخطيط، شرائح الملاحظات). للقراءة فقط [IHyperlinkQueries](../ihyperlinkqueries/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_Image](./get_image/)(**int32_t**) | يعيد الصورة في العرض التقديمي عند الفهرس المحدد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImageCollection](../iimagecollection/)\> [get_Images](./get_images/)() | يعيد مجموعة جميع الصور في العرض التقديمي. للقراءة فقط [IImageCollection](../iimagecollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [get_LayoutSlide](./get_layoutslide/)(**int32_t**) | يعيد شريحة التخطيط حسب الفهرس. للقراءة فقط [Aspose::Slides::ILayoutSlide](../ilayoutslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGlobalLayoutSlideCollection](../igloballayoutslidecollection/)\> [get_LayoutSlides](./get_layoutslides/)() | يعيد قائمة جميع شرائح التخطيط المعرفة في العرض التقديمي. للقراءة فقط [IGlobalLayoutSlideCollection](../igloballayoutslidecollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](../imasterslide/)\> [get_Master](./get_master/)(**int32_t**) | يعيد شريحة رئيسية معرفة في العرض التقديمي عند الفهرس المحدد. للقراءة فقط [Aspose::Slides::IMasterSlide](../imasterslide/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterHandoutSlideManager](../imasterhandoutslidemanager/)\> [get_MasterHandoutSlideManager](./get_masterhandoutslidemanager/)() | يعيد مدير نموذج النشرة الرئيسية. للقراءة فقط [IMasterHandoutSlideManager](../imasterhandoutslidemanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterNotesSlideManager](../imasternotesslidemanager/)\> [get_MasterNotesSlideManager](./get_masternotesslidemanager/)() | يعيد مدير نموذج الملاحظات الرئيسية. للقراءة فقط [IMasterNotesSlideManager](../imasternotesslidemanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlideCollection](../imasterslidecollection/)\> [get_Masters](./get_masters/)() | يعيد قائمة جميع الشرائح الرئيسية المعرفة في العرض التقديمي. للقراءة فقط [IMasterSlideCollection](../imasterslidecollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Theme::IMasterTheme](../../aspose.slides.theme/imastertheme/)\> [get_MasterTheme](./get_mastertheme/)() | يعيد سمة القالب الرئيسي للعرض التقديمي. للقراءة فقط [Theme::IMasterTheme](../../aspose.slides.theme/imastertheme/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[INotesSize](../inotessize/)\> [get_NotesSize](./get_notessize/)() | يعيد كائن حجم شريحة الملاحظات. للقراءة فقط [INotesSize](../inotessize/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](./)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | يعيد العرض التقديمي. للقراءة فقط [IPresentation](./). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProtectionManager](../iprotectionmanager/)\> [get_ProtectionManager](./get_protectionmanager/)() | يحصل على مدير الأذونات لهذا العرض التقديمي. للقراءة فقط [IProtectionManager](../iprotectionmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_Section](./get_section/)(**int32_t**) | يعيد قسم شريحة معرف في العرض التقديمي عند الفهرس المحدد. للقراءة فقط [Aspose::Slides::ISection](../isection/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISectionCollection](../isectioncollection/)\> [get_Sections](./get_sections/)() | يعيد قائمة جميع أقسام الشرائح المعرفة في العرض التقديمي. للقراءة فقط [ISectionCollection](../isectioncollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabelCollection](../isensitivitylabelcollection/)\> [get_SensitivityLabels](./get_sensitivitylabels/)() | يعيد مجموعة تسميات الحساسية المطبقة على مستند العرض التقديمي. للقراءة فقط [ISensitivityLabelCollection](../isensitivitylabelcollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_Slide](./get_slide/)(**int32_t**) | يعيد شريحة معرفة في العرض التقديمي عند الفهرس المحدد. للقراءة فقط [Aspose::Slides::ISlide](../islide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideCollection](../islidecollection/)\> [get_Slides](./get_slides/)() | يعيد قائمة جميع الشرائح المعرفة في العرض التقديمي. للقراءة فقط [ISlideCollection](../islidecollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideSize](../islidesize/)\> [get_SlideSize](./get_slidesize/)() | يعيد كائن حجم الشريحة. للقراءة فقط [ISlideSize](../islidesize/). |
| virtual [Aspose::Slides::SourceFormat](../sourceformat/) [get_SourceFormat](./get_sourceformat/)() | يعيد معلومات حول التنسيق الذي تم تحميل العرض التقديمي منه. للقراءة فقط [IPresentation::get_SourceFormat](./get_sourceformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/)\> [get_VbaProject](./get_vbaproject/)() | يحصل على مشروع VBA مع ماكروهات العرض التقديمي. للقراءة [Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\> [get_Video](./get_video/)(**int32_t**) | يعيد ملف الفيديو المضمّن في العرض التقديمي عند الفهرس المحدد. للقراءة فقط [Aspose::Slides::IVideo](../ivideo/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IVideoCollection](../ivideocollection/)\> [get_Videos](./get_videos/)() | يعيد مجموعة جميع ملفات الفيديو المضمّنة في العرض التقديمي. للقراءة فقط [IVideoCollection](../ivideocollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IViewProperties](../iviewproperties/)\> [get_ViewProperties](./get_viewproperties/)() | يحصل على خصائص العرض الواسعة للعرض التقديمي. للقراءة فقط [IViewProperties](../iviewproperties/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد الإشارة المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظيرة طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). تمكّن تجزئة الكائنات المخصّصة. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | يعيد كائنات صورة مصغرة لجميع شرائح العرض التقديمي. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | يعيد كائنات صورة مصغرة (Bitmap) للشرائح المحددة من العرض التقديمي. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, **float**, **float**) | يعيد كائنات صورة مصغرة لجميع شرائح العرض التقديمي مع تحجيم مخصّص. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, **float**, **float**) | يعيد كائنات صورة مصغرة للشرائح المحددة من العرض التقديمي مع تحجيم مخصّص. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::Drawing::Size](../../system.drawing/size/)) | يعيد كائنات صورة مصغرة لجميع شرائح العرض التقديمي بالحجم المحدد. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [System::Drawing::Size](../../system.drawing/size/)) | يعيد كائنات صورة مصغرة للشرائح المحددة من العرض التقديمي بالحجم المحدد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [GetSlideById](./getslidebyid/)(**uint32_t**) | يعيد [Slide](../slide/) أو [MasterSlide](../masterslide/) أو [LayoutSlide](../layoutslide/) بحسب المعرف. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظيرة نداء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual void [HighlightRegex](./highlightregex/)([System::SharedPtr](../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../system.text.regularexpressions/regex/)\>, [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) | يُبرز جميع تطابقات التعبير النمطي باللون المحدد. |
| virtual void [HighlightText](./highlighttext/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/)) | يُبرز جميع تطابقات النص النموذجي باللون المحدد. |
| virtual void [HighlightText](./highlighttext/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[ITextSearchOptions](../itextsearchoptions/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) | يُبرز جميع تطابقات النص النموذجي باللون المحدد. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظيرة عامل C# 'is'. |
| virtual void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)() | يدمج المقاطع ذات التنسيق نفسه في جميع الفقرات داخل جميع الأشكال المقبولة في جميع الشرائح. |
| void [Lock](../../system/object/lock/)() | ينفّذ عملية القفل في تعليمة C# lock(). استدعِها مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظيرة طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). تمكّن استنساخ الأنواع المخصّصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيّئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، وإنما يهيّئ كائنًا جديدًا ويُمكّن إنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، وإنما يهيّئ كائنًا جديدًا ويُمكّن إنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالإشارة. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالإشارة. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) في حالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) في حالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد الإشارة المشتركة بالقيمة المحددة. |
| virtual void [ReplaceRegex](./replaceregex/)([System::SharedPtr](../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../system.text.regularexpressions/regex/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) | يستبدل جميع تطابقات التعبير النمطي بالسلسلة المحددة. |
| virtual void [ReplaceText](./replacetext/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[ITextSearchOptions](../itextsearchoptions/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) | يستبدل جميع مرات ظهور النص المحدد بنص آخر محدد. |
| virtual void [Save](./save/)([System::String](../../system/string/), [Export::SaveFormat](../../aspose.slides.export/saveformat/)) | يحفظ جميع شرائح العرض التقديمي إلى ملف بالتنسيق المحدد. |
| virtual void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) | يحفظ جميع شرائح العرض التقديمي إلى تدفق بالتنسيق المحدد. |
| virtual void [Save](./save/)([System::String](../../system/string/), [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) | يحفظ جميع شرائح العرض التقديمي إلى ملف بالتنسيق المحدد ومع خيارات إضافية. |
| virtual void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) | يحفظ جميع شرائح العرض التقديمي إلى تدفق بالتنسيق المحدد ومع خيارات إضافية. |
| virtual void [Save](./save/)([System::String](../../system/string/), [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) | يحفظ الشرائح المحددة من العرض التقديمي إلى ملف بالتنسيق المحدد. |
| virtual void [Save](./save/)([System::String](../../system/string/), [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) | يحفظ الشرائح المحددة من العرض التقديمي إلى ملف بالتنسيق المحدد. |
| virtual void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) | يحفظ الشرائح المحددة من العرض التقديمي إلى تدفق بالتنسيق المحدد. |
| virtual void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) | يحفظ الشرائح المحددة من العرض التقديمي إلى تدفق بالتنسيق المحدد. |
| virtual void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../aspose.slides.export.xaml/ixamloptions/)\>) | يحفظ جميع شرائح العرض التقديمي إلى مجموعة من الملفات التي تمثل تنسيق XAML. |
| virtual void [set_CurrentDateTime](./set_currentdatetime/)([System::DateTime](../../system/datetime/)) | يضبط التاريخ والوقت اللذان سيستبدلان محتوى حقول datetime. وقت إنشاء كائن [Presentation](../presentation/) هذا هو الافتراضي. اكتب [System::DateTime](../../system/datetime/). |
| virtual void [set_DocumentProperty](./set_documentproperty/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | يضبط الخاصية المخصّصة المعرفة بالاسم. |
| virtual void [set_FirstSlideNumber](./set_firstslidenumber/)(**int32_t**) | يمثل رقم الشريحة الأولى في العرض التقديمي. اكتب **int32_t**. |
| virtual void [set_VbaProject](./set_vbaproject/)([System::SharedPtr](../../system/sharedptr/)\<[Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/)\>) | يحصل على مشروع VBA مع ماكروهات العرض التقديمي. اكتب [Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط المعامل النمطي الـ n'th كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ استعمل مؤشرات ذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ استعمل مؤشرات ذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظيرة طريقة C# [Object.ToString()](../../system/object/tostring/). تمكّن تحويل الكائنات المخصّصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ فك قفل تعليمة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استعمل مؤشرات ذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استعمل مؤشرات ذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [IPresentationComponent](../ipresentationcomponent/)
* الفئة [IDisposable](../../system/idisposable/)
* مساحة الاسم [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)