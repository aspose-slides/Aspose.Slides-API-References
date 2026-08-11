---
title: ISummaryZoomSection
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل كائن Summary Zoom Section في إطار Summary Zoom.
type: docs
weight: 3927
url: /ar/aspose.slides/isummaryzoomsection/
---
## فئة ISummaryZoomSection

يمثل كائن Summary Zoom [Section](../section/) في إطار Summary Zoom.

```cpp
class ISummaryZoomSection : public virtual Aspose::Slides::ISectionZoomFrame
```

## الأساليب

| طريقة | الوصف |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | يضيف عنصر نائب جديد إذا لم يوجد ويضبط خصائص العنصر النائب إلى عنصر محدد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتَبَر NaNانان متساويين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتَبَر NaNانان متساويين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | يرجع النص البديل المرتبط بالشكل. اقرأ [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | يرجع عنوان النص البديل المرتبط بالشكل. اقرأ [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | تحدد الخاصية كيفية عرض الشكل في وضع العرض بالأبيض والأسود. اقرأ [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | يرجع عدد مواقع الاتصال على الشكل. قراءة فقط **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | يرجع البيانات المخصصة للشكل. قراءة فقط [ICustomData](../icustomdata/). |
| virtual [System::String](../../system/string/) [get_Description](./get_description/)() | يرجع الوصف النصي لكائن Summary Zoom [Section](../section/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | يرجع كائن [EffectFormat](../effectformat/) الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. قراءة فقط [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | يرجع كائن [FillFormat](../fillformat/) الذي يحتوي على خصائص تنسيق التعبئة لشكل. قراءة فقط [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | يرجع خصائص إطار الشكل. اقرأ [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | يرجع أقفال الشكل. قراءة فقط [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | يُحصل على ارتفاع الشكل، مقاسًا بالنقاط. قراءة **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | يحدد ما إذا كان الشكل مخفيًا. قراءة **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | يرجع الارتباط التشعبي المعرفة للنقر بالفأرة. اقرأ [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | مدير الارتباطات التشعبية قراءة فقط [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | يرجع الارتباط التشعبي المعرفة للتمرير بالفأرة. اقرأ [IHyperlink](../ihyperlink/). |
| virtual [ZoomImageType](../zoomimagetype/) [get_ImageType](../izoomobject/get_imagetype/)() | يُحصل على نوع الصورة لكائن التكبير. اقرأ [ZoomImageType](../zoomimagetype/). القيمة الافتراضية: Preview |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | يُحصل على خيار 'وضع علامة كزخرفة' قراءة/كتابة **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | يحدد ما إذا كان الشكل مجموعة. قراءة فقط **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | يحدد ما إذا كان الشكل حاملاً للنص. قراءة فقط **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | يرجع كائن [LineFormat](../lineformat/) الذي يحتوي على خصائص تنسيق الخط لشكل. قراءة فقط [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | يرجع اسم الشكل. اقرأ [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | يرجع معرفًا فريدًا محصورًا بالعرض يتظل ثابتًا طوال عمر الشكل ويسمح لبرنامج PowerPoint أو شفرة التفاعل بالإشارة إلى الشكل بثقة من أي مكان في المستند. قراءة فقط **uint32_t**. انظر أيضًا [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | يرجع كائن [GroupShape](../groupshape/) الأب إذا كان الشكل مجموعة. وإلا يرجع null. قراءة فقط [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | يرجع العنصر النائب لشكل. قراءة فقط [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | يرجع العرض التقديمي. قراءة فقط [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | يرجع خصائص إطار الشكل الخام. اقرأ [IShapeFrame](../ishapeframe/). |
| virtual **bool** [get_ReturnToParent](../izoomobject/get_returntoparent/)() | يُحصل على سلوك التنقل في عرض الشرائح. قراءة **bool**. القيمة الافتراضية: false |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | يرجع عدد درجات دوران الشكل المحدد حول المحور z. القيمة الإيجابية تشير إلى دوران باتجاه عقارب الساعة؛ والقيمة السلبية تشير إلى دوران عكس اتجاه عقارب الساعة. قراءة **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | يرجع أقفال الشكل. قراءة فقط [IBaseShapeLock](../ibaseshapelock/). |
| virtual **bool** [get_ShowBackground](../izoomobject/get_showbackground/)() | يُحصل على قيمة تحدد ما إذا كان Zoom سيستخدم خلفية الشريحة الهدف. قراءة **bool**. القيمة الافتراضية: true |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | يرجع الشريحة الأساسية. قراءة فقط [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_TargetSection](../isectionzoomframe/get_targetsection/)() | يُحصل على كائن القسم المرتبط به كائن Zoom [Section](../section/). اقرأ [ISection](../isection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | يرجع كائن [ThreeDFormat](../threedformat/) الذي يحتوي على خصائص تنسيق الخط لشكل. قراءة فقط [IThreeDFormat](../ithreedformat/). |
| virtual [System::String](../../system/string/) [get_Title](./get_title/)() | يرجع عنوان النص لكائن Summary Zoom [Section](../section/). |
| virtual **float** [get_TransitionDuration](../izoomobject/get_transitionduration/)() | يُحصل على مدة الانتقال بين Zoom والشريحة. قراءة **float**. القيمة الافتراضية: 1.0f |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | يرجع معرفًا داخليًا محصورًا بالعرض مخصصًا للاستخدام من قبل الإضافات أو الشيفرة الأخرى. نظرًا لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، فلا يجب اعتبارها مفتاحًا فريدًا دائمًا. قراءة فقط **uint32_t**. انظر أيضًا [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../ishape/get_width/)() | يُحصل على عرض الشكل، مقاسًا بالنقاط. قراءة **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | يُحصل على إحداثي x للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. قراءة **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | يُحصل على إحداثي y للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. قراءة **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../izoomobject/get_zoomimage/)() | يُحصل على صورة كائن التكبير. اقرأ [IPPImage](../ippimage/). |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | يرجع موضع الشكل في ترتيب z. تُرجع Shapes[0] الشكل الموجود في مؤخرة ترتيب z، وتُرجع Shapes[Shapes.Count - 1] الشكل الموجود في مقدمة ترتيب z. قراءة فقط **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | يرجع شكل عنصر نائب أساسي (شكل من التخطيط و/أو الشريحة الرئيسية الذي يتم وراثة الشكل الحالي منه). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يُحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | يرجع صورة مصغرة للشكل. يُستخدم نوع حدود الصورة المصغرة للشكل [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) كافتراضي. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | يرجع صورة مصغرة للشكل. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يُحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. تماثل عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يُنفذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ للأنواع الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ للأنواع الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجعية مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | يضبط النص البديل المرتبط بالشكل. اكتب [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | يضبط عنوان النص البديل المرتبط بالشكل. اكتب [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | الخاصية تحدد كيفية عرض الشكل في وضع العرض بالأبيض والأسود. اكتب [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Description](./set_description/)([System::String](../../system/string/)) | يرجع الوصف النصي لكائن Summary Zoom [Section](../section/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | يضبط خصائص إطار الشكل. اكتب [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | يضبط ارتفاع الشكل، مقاسًا بالنقاط. اكتب **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | يحدد ما إذا كان الشكل مخفيًا. اكتب **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | يضبط الارتباط التشعبي المعرفة للنقر بالفأرة. اكتب [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | يضبط الارتباط التشعبي المعرفة للتمرير بالفأرة. اكتب [IHyperlink](../ihyperlink/). |
| virtual void [set_ImageType](../izoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) | يضبط نوع الصورة لكائن التكبير. اكتب [ZoomImageType](../zoomimagetype/). القيمة الافتراضية: Preview |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | يضبط خيار 'وضع علامة كزخرفة' قراءة/كتابة **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | يضبط اسم الشكل. اكتب [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | يضبط خصائص إطار الشكل الخام. اكتب [IShapeFrame](../ishapeframe/). |
| virtual void [set_ReturnToParent](../izoomobject/set_returntoparent/)(**bool**) | يضبط سلوك التنقل في عرض الشرائح. اكتب **bool**. القيمة الافتراضية: false |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | يضبط عدد درجات دوران الشكل المحدد حول المحور z. القيمة الإيجابية تشير إلى دوران باتجاه عقارب الساعة؛ والقيمة السلبية تشير إلى دوران عكس اتجاه عقارب الساعة. اكتب **float**. |
| virtual void [set_ShowBackground](../izoomobject/set_showbackground/)(**bool**) | يضبط القيمة التي تحدد ما إذا كان Zoom سيستخدم خلفية الشريحة الهدف. اكتب **bool**. القيمة الافتراضية: true |
| virtual void [set_TargetSection](../isectionzoomframe/set_targetsection/)([System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) | يضبط كائن القسم المرتبط به كائن Zoom [Section](../section/). اكتب [ISection](../isection/). |
| virtual void [set_Title](./set_title/)([System::String](../../system/string/)) | يرجع عنوان النص لكائن Summary Zoom [Section](../section/). |
| virtual void [set_TransitionDuration](../izoomobject/set_transitionduration/)(**float**) | يضبط مدة الانتقال بين Zoom والشريحة. اكتب **float**. القيمة الافتراضية: 1.0f |
| virtual void [set_Width](../ishape/set_width/)(**float**) | يضبط عرض الشكل، مقاسًا بالنقاط. اكتب **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | يضبط إحداثي x للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. اكتب **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | يضبط إحداثي y للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. اكتب **float**. |
| virtual void [set_ZoomImage](../izoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) | يضبط صورة لكائن التكبير. اكتب [IPPImage](../ippimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الحجة النمطية الـ n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يُحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويُعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يُنفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يُنفذ إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | يحفظ محتوى [Shape](../shape/) كملف SVG. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | يحفظ محتوى [Shape](../shape/) كملف SVG. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## أنظر أيضًا

* فئة [ISectionZoomFrame](../isectionzoomframe/)
* مساحة الاسم [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)