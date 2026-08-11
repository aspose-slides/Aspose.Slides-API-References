---
title: Presentation
second_title: مرجع API ل Aspose.Slides للغة C++
description: يمثّل عرض Microsoft PowerPoint.
type: docs
weight: 4837
url: /ar/aspose.slides/presentation/
---
## فئة Presentation

يمثّل عرض Microsoft PowerPoint.

```cpp
class Presentation : public Aspose::Slides::IPresentation,
                     public Aspose::Slides::IDOMObject
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| void [Dispose](./dispose/)() override | يطلق جميع الموارد المستخدمة بواسطة كائن [Presentation](./) هذا. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر قيمتا NaN متساويتين رغم أنه وفقًا للمعيار IEC 60559:1989 فإن NaN لا تساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر قيمتا NaN متساويتين رغم أنه وفقًا للمعيار IEC 60559:1989 فإن NaN لا تساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ICustomXmlPart](../icustomxmlpart/)\>\> [get_AllCustomXmlParts](./get_allcustomxmlparts/)() override | يعيد جميع أجزاء البيانات المخصصة في العرض. قراءة فقط [ICustomXmlPart](../icustomxmlpart/)[]. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Audio](./get_audio/)(**int32_t**) override | يعيد ملف الصوت المضمن في العرض عند الفهرس المحدد. قراءة فقط [Aspose::Slides::IAudio](../iaudio/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioCollection](../iaudiocollection/)\> [get_Audios](./get_audios/)() override | يعيد مجموعة جميع ملفات الصوت المضمنة في العرض. قراءة فقط [IAudioCollection](../iaudiocollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\> [get_CommentAuthor](./get_commentauthor/)(**int32_t**) override | يعيد مؤلف التعليق عند الفهرس المحدد. قراءة فقط [Aspose::Slides::ICommentAuthor](../icommentauthor/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthorCollection](../icommentauthorcollection/)\> [get_CommentAuthors](./get_commentauthors/)() override | يعيد مجموعة مؤلفي التعليقات. قراءة فقط [ICommentAuthorCollection](../icommentauthorcollection/). |
| [System::DateTime](../../system/datetime/) [get_CurrentDateTime](./get_currentdatetime/)() override | يعيد التاريخ والوقت اللذين سيستبدلان محتوى حقول datetime. وقت إنشاء كائن [Presentation](./) هذا افتراضيًا. قراءة [System::DateTime](../../system/datetime/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() override | يعيد البيانات المخصصة للعرض. قراءة فقط [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_DefaultTextStyle](./get_defaulttextstyle/)() override | يعيد نمط النص الافتراضي للأشكال. قراءة فقط [ITextStyle](../itextstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDigitalSignature](../idigitalsignature/)\> [get_DigitalSignature](./get_digitalsignature/)(**int32_t**) override | يعيد التوقيع الرقمي المستخدم لتوقيع العرض عند الفهرس المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDigitalSignatureCollection](../idigitalsignaturecollection/)\> [get_DigitalSignatures](./get_digitalsignatures/)() override | يعيد مجموعة التواقيع المستخدمة لتوقيع العرض. قراءة فقط [IDigitalSignatureCollection](../idigitalsignaturecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [get_DocumentProperties](./get_documentproperties/)() override | يعيد كائن [DocumentProperties](../documentproperties/) الذي يحتوي على خصائص المستند القياسية والمخصصة. قراءة فقط [IDocumentProperties](../idocumentproperties/). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_DocumentProperty](./get_documentproperty/)([System::String](../../system/string/)) override | يعيد الخاصية المخصصة المعرفة بالاسم. |
| **int32_t** [get_FirstSlideNumber](./get_firstslidenumber/)() override | يمثل رقم الشريحة الأولى في العرض |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontsManager](../ifontsmanager/)\> [get_FontsManager](./get_fontsmanager/)() override | يعيد مدير الخطوط. قراءة فقط [IFontsManager](../ifontsmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentationHeaderFooterManager](../ipresentationheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() override | يعيد مدير الترويسة/التذييل الفعلي. قراءة فقط [IPresentationHeaderFooterManager](../ipresentationheaderfootermanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](./get_hyperlinkqueries/)() override | يوفر وصولًا سهلاً إلى جميع الروابط التشعبية الموجودة في جميع شرائح العرض (ليس في الشريحة الأصلية، تخطيط، شرائح الملاحظات). قراءة فقط [IHyperlinkQueries](../ihyperlinkqueries/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_Image](./get_image/)(**int32_t**) override | يعيد الصورة في العرض عند الفهرس المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImageCollection](../iimagecollection/)\> [get_Images](./get_images/)() override | يعيد مجموعة جميع الصور في العرض. قراءة فقط [IImageCollection](../iimagecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [get_LayoutSlide](./get_layoutslide/)(**int32_t**) override | يعيد شريحة التخطيط حسب الفهرس. قراءة فقط [Aspose::Slides::ILayoutSlide](../ilayoutslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGlobalLayoutSlideCollection](../igloballayoutslidecollection/)\> [get_LayoutSlides](./get_layoutslides/)() override | يعيد قائمة بجميع شرائح التخطيط المعرفة في العرض. قراءة فقط [IGlobalLayoutSlideCollection](../igloballayoutslidecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](../imasterslide/)\> [get_Master](./get_master/)(**int32_t**) override | يعيد شريحة رئيسية معرفة في العرض عند الفهرس المحدد. قراءة فقط [Aspose::Slides::IMasterSlide](../imasterslide/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterHandoutSlideManager](../imasterhandoutslidemanager/)\> [get_MasterHandoutSlideManager](./get_masterhandoutslidemanager/)() override | يعيد مدير نسخة النشرة الرئيسية. قراءة فقط [IMasterHandoutSlideManager](../imasterhandoutslidemanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterNotesSlideManager](../imasternotesslidemanager/)\> [get_MasterNotesSlideManager](./get_masternotesslidemanager/)() override | يعيد مدير ملاحظات رئيسية. قراءة فقط [IMasterNotesSlideManager](../imasternotesslidemanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlideCollection](../imasterslidecollection/)\> [get_Masters](./get_masters/)() override | يعيد قائمة بجميع الشرائح الرئيسة المعرفة في العرض. قراءة فقط [IMasterSlideCollection](../imasterslidecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IMasterTheme](../../aspose.slides.theme/imastertheme/)\> [get_MasterTheme](./get_mastertheme/)() override | يعيد سمة الرئيسة. قراءة فقط [Theme::IMasterTheme](../../aspose.slides.theme/imastertheme/). |
| [System::SharedPtr](../../system/sharedptr/)\<[INotesSize](../inotessize/)\> [get_NotesSize](./get_notessize/)() override | يعيد كائن حجم شريحة الملاحظات. قراءة فقط [INotesSize](../inotessize/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProtectionManager](../iprotectionmanager/)\> [get_ProtectionManager](./get_protectionmanager/)() override | يحصل على مدير أذونات هذا العرض. قراءة فقط [IProtectionManager](../iprotectionmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_Section](./get_section/)(**int32_t**) override | يعيد قسم شريحة معرف في العرض عند الفهرس المحدد. قراءة فقط [Aspose::Slides::ISection](../isection/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ISectionCollection](../isectioncollection/)\> [get_Sections](./get_sections/)() override | يعيد قائمة بجميع أقسام الشرائح المعرفة في العرض. قراءة فقط [ISectionCollection](../isectioncollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabelCollection](../isensitivitylabelcollection/)\> [get_SensitivityLabels](./get_sensitivitylabels/)() override | يعيد مجموعة تسميات الحساسية المطبقة على مستند العرض. قراءة فقط [ISensitivityLabelCollection](../isensitivitylabelcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_Slide](./get_slide/)(**int32_t**) override | يعيد شريحة معرفة في العرض عند الفهرس المحدد. قراءة فقط [Aspose::Slides::ISlide](../islide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideCollection](../islidecollection/)\> [get_Slides](./get_slides/)() override | يعيد قائمة بجميع الشرائح المعرفة في العرض. قراءة فقط [ISlideCollection](../islidecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::SlideShowSettings](../slideshowsettings/)\> [get_SlideShowSettings](./get_slideshowsettings/)() const | يعيد إعدادات عرض الشرائح للعرض. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideSize](../islidesize/)\> [get_SlideSize](./get_slidesize/)() override | يعيد كائن حجم الشريحة. قراءة فقط [ISlideSize](../islidesize/). |
| [Aspose::Slides::SourceFormat](../sourceformat/) [get_SourceFormat](./get_sourceformat/)() override | يعيد معلومات عن الصيغة التي تم تحميل العرض منها. قراءة فقط [SourceFormat](../sourceformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/)\> [get_VbaProject](./get_vbaproject/)() override | يحصل على مشروع VBA مع ماكروات العرض. قراءة [Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\> [get_Video](./get_video/)(**int32_t**) override | يعيد ملف الفيديو المضمن في العرض عند الفهرس المحدد. قراءة فقط [Aspose::Slides::IVideo](../ivideo/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideoCollection](../ivideocollection/)\> [get_Videos](./get_videos/)() override | يعيد مجموعة جميع ملفات الفيديو المضمنة في العرض. قراءة فقط [IVideoCollection](../ivideocollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IViewProperties](../iviewproperties/)\> [get_ViewProperties](./get_viewproperties/)() override | يحصل على خصائص العرض العامة. قراءة فقط [IViewProperties](../iviewproperties/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد الإشارة المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) override | يعيد كائنات Image لجميع شرائح العرض. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) override | يعيد كائنات Thumbnail Image للشرائح المحددة من العرض. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, **float**, **float**) override | يعيد كائنات Thumbnail Image لجميع شرائح العرض مع تحجيم مخصص. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, **float**, **float**) override | يعيد كائنات Thumbnail Image للشرائح المحددة من العرض مع تحجيم مخصص. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::Drawing::Size](../../system.drawing/size/)) override | يعيد كائنات Thumbnail Image لجميع شرائح العرض بالحجم المحدد. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [System::Drawing::Size](../../system.drawing/size/)) override | يعيد كائنات Thumbnail Image للشرائح المحددة من العرض بالحجم المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [GetSlideById](./getslidebyid/)(**uint32_t**) override | يعيد [Slide](../slide/) أو [MasterSlide](../masterslide/) أو [LayoutSlide](../layoutslide/) حسب المعرّف. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| void [HighlightRegex](./highlightregex/)([System::SharedPtr](../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../system.text.regularexpressions/regex/)\>, [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | يبرز جميع التطابقات للتعبير النمطي باللون المحدد. |
| void [HighlightText](./highlighttext/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/)) override | يبرز جميع تطابقات النص العيني باللون المحدد. |
| void [HighlightText](./highlighttext/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[ITextSearchOptions](../itextsearchoptions/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | يبرز جميع تطابقات النص العيني باللون المحدد. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. مماثل لمعامل C# 'is'. |
| void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)() override | يجمع النصوص المتتابعة ذات التنسيق المتطابق في جميع الفقرات بجميع الأشكال المقبولة في جميع الشرائح. |
| void [Lock](../../system/object/lock/)() | يطبق عبارة القفل C# lock() . استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
|  [Presentation](./presentation/)() | هذا المنشئ ينشئ عرضًا جديدًا من الصفر. يحتوي العرض المُنشأ على شريحة فارغة واحدة. |
|  [Presentation](./presentation/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../loadoptions/)\>) | هذا المنشئ ينشئ عرضًا جديدًا من الصفر. يحتوي العرض المُنشأ على شريحة فارغة واحدة. |
|  [Presentation](./presentation/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | هذا المنشئ هو الآلية الأساسية لقراءة [Presentation](./) موجود مسبقًا. |
|  [Presentation](./presentation/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../loadoptions/)\>) | هذا المنشئ هو الآلية الأساسية لقراءة [Presentation](./) موجود مسبقًا. |
|  [Presentation](./presentation/)([System::String](../../system/string/)) | هذا المنشئ يحصل على مسار ملف المصدر الذي تُقرأ منه محتويات [Presentation](./). |
|  [Presentation](./presentation/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../loadoptions/)\>) | هذا المنشئ يحصل على مسار ملف المصدر الذي تُقرأ منه محتويات [Presentation](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن القيمة المرجعية مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد الإشارة المشتركة بالقيمة المحددة. |
| void [ReplaceRegex](./replaceregex/)([System::SharedPtr](../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../system.text.regularexpressions/regex/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | يستبدل جميع التطابقات للتعبير النمطي بالسلسلة المحددة. |
| void [ReplaceText](./replacetext/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[ITextSearchOptions](../itextsearchoptions/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | يستبدل جميع مرات ظهور النص المحدد بنص آخر محدد. |
| void [Save](./save/)([System::String](../../system/string/), [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | يحفظ جميع شرائح العرض إلى ملف بالصيغ المحددة. |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | يحفظ جميع شرائح العرض إلى تدفق بالصيغ المحددة. |
| void [Save](./save/)([System::String](../../system/string/), [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | يحفظ جميع شرائح العرض إلى ملف بالصيغ المحددة ومع خيارات إضافية. |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | يحفظ جميع شرائح العرض إلى تدفق بالصيغ المحددة ومع خيارات إضافية. |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../aspose.slides.export.xaml/ixamloptions/)\>) override | يحفظ جميع شرائح العرض إلى مجموعة ملفات تمثل ترميز XAML. |
| void [Save](./save/)([System::String](../../system/string/), [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | يحفظ الشرائح المحددة من العرض إلى ملف بالصيغ المحددة مع الحفاظ على أرقام الصفحات. |
| void [Save](./save/)([System::String](../../system/string/), [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | يحفظ الشرائح المحددة من العرض إلى ملف بالصيغ المحددة مع الحفاظ على أرقام الصفحات. |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | يحفظ الشرائح المحددة من العرض إلى تدفق بالصيغ المحددة مع الحفاظ على أرقام الصفحات. |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | يحفظ الشرائح المحددة من العرض إلى تدفق بالصيغ المحددة مع الحفاظ على أرقام الصفحات. |
| void [set_CurrentDateTime](./set_currentdatetime/)([System::DateTime](../../system/datetime/)) override | يضبط التاريخ والوقت الذين سيستبدلان محتوى حقول datetime. وقت إنشاء كائن [Presentation](./) هذا افتراضيًا. كتابة [System::DateTime](../../system/datetime/). |
| void [set_DocumentProperty](./set_documentproperty/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | يضبط الخاصية المخصصة المعرفة بالاسم. |
| void [set_FirstSlideNumber](./set_firstslidenumber/)(**int32_t**) override | يمثل رقم الشريحة الأولى في العرض |
| void [set_VbaProject](./set_vbaproject/)([System::SharedPtr](../../system/sharedptr/)\<[Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/)\>) override | يضبط مشروع VBA مع ماكروات العرض. كتابة [Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n كإشارة ضعيفة (بدلاً من مشاركة). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشترك. لا يجب استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد الإشارة المشترك. لا يجب استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة نصية. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يطبق بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يطبق عبارة القفل C# lock() . استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا يجب استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد الإشارة الضعيفة. لا يجب استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## ملاحظات

المثال التالي يوضح كيفية إنشاء PowerPoint [Presentation](./). 
```cpp
// إنشاء كائن Presentation يمثل ملف عرض
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

// احصل على الشريحة الأولى
auto slide = presentation->get_Slides()->idx_get(0);
// إضافة شكل تلقائي من النوع خط
slide->get_Shapes()->AddAutoShape(ShapeType::Line, 50.0f, 150.0f, 300.0f, 0.0f);
// حفظ ملف العرض.
presentation->Save(u"NewPresentation_out.pptx", SaveFormat::Pptx);
```
المثال التالي يوضح كيفية فتح وحفظ [Presentation](./). 
```cpp
// تحميل أي ملف مدعوم في Presentation على سبيل المثال ppt، pptx، odp إلخ.
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"Sample.odp");

// حفظ ملف العرض.
presentation->Save(u"OutputPresenation.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* الفئة [IPresentation](../ipresentation/)
* الفئة [IDOMObject](../idomobject/)
* مساحة الأسماء [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)