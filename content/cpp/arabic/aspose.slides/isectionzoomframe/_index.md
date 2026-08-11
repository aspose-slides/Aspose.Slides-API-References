---
title: ISectionZoomFrame
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يمثل كائن Section Zoom في شريحة.
type: docs
weight: 3602
url: /ar/aspose.slides/isectionzoomframe/
---
## ISectionZoomFrame فئة

يمثل كائن [Section](../section/) Zoom في شريحة.

```cpp
class ISectionZoomFrame : public virtual Aspose::Slides::IZoomObject
```

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | يضيف عنصر نائب جديد إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى عنصر محدد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالة C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | محاكاة مقارنة النقطة العائمة بنمط C# حيث تُعتَبر قيمتي NaN متساويتين على الرغم من أنه وفقًا لـ IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | محاكاة مقارنة النقطة العائمة بنمط C# حيث تُعتَبر قيمتي NaN متساويتين على الرغم من أنه وفقًا لـ IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | يعيد النص البديل المرتبط بشكل. اقرأ [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | يعيد عنوان النص البديل المرتبط بشكل. اقرأ [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | تحدد الخاصية كيف سيُعرض الشكل في وضع العرض بالأبيض والأسود. اقرأ [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | يعيد عدد نقاط الاتصال على الشكل. قراءة فقط **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | يعيد البيانات المخصصة للشكل. قراءة فقط [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | يعيد كائن [EffectFormat](../effectformat/) الذي يحتوي على التأثيرات البكسلية المطبقة على شكل. قراءة فقط [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | يعيد كائن [FillFormat](../fillformat/) الذي يحتوي على خصائص تنسيق التعبئة لشكل. قراءة فقط [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | يعيد خصائص إطار الشكل. اقرأ [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | يعيد أقفال الشكل. قراءة فقط [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | يحصل على ارتفاع الشكل، مقاسًا بالنقاط. قراءة **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | يحدد ما إذا كان الشكل مخفيًا. قراءة **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | يعيد الارتباط التشعبي المحدد للنقر بالفأرة. اقرأ [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | مدير الارتباطات التشعبية قراءة فقط [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | يعيد الارتباط التشعبي المحدد عند تحريك الفأرة فوقه. اقرأ [IHyperlink](../ihyperlink/). |
| virtual [ZoomImageType](../zoomimagetype/) [get_ImageType](../izoomobject/get_imagetype/)() | يحصل على نوع الصورة لكائن Zoom. اقرأ [ZoomImageType](../zoomimagetype/). القيمة الافتراضية: Preview |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | يحصل على خيار 'Mark as decorative' للقراءة/الكتابة **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | يحدد ما إذا كان الشكل مجموعة. قراءة فقط **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | يحدد ما إذا كان الشكل TextHolder. قراءة فقط **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | يعيد كائن [LineFormat](../lineformat/) الذي يحتوي على خصائص تنسيق الخط لشكل. قراءة فقط [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | يعيد اسم الشكل. اقرأ [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | يعيد معرفًا فريدًا يقتصر على الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو كود التفاعل بالإشارة إلى الشكل بثقة من أي مكان في المستند. قراءة فقط **uint32_t**. انظر أيضًا [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | يعيد كائن [GroupShape](../groupshape/) الأب إذا كان الشكل مجموعة. وإلا يعيد null. قراءة فقط [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | يعيد العنصر النائب لشكل. قراءة فقط [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | يعيد العرض التقديمي. قراءة فقط [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | يعيد خصائص إطار الشكل الخام. اقرأ [IShapeFrame](../ishapeframe/). |
| virtual **bool** [get_ReturnToParent](../izoomobject/get_returntoparent/)() | يحصل على سلوك التنقل في عرض الشرائح. قراءة **bool**. القيمة الافتراضية: false |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | يعيد عدد الدرجات التي يدور فيها الشكل المحدد حول محور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ والسالبة إلى عكسها. قراءة **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | يعيد أقفال الشكل. قراءة فقط [IBaseShapeLock](../ibaseshapelock/). |
| virtual **bool** [get_ShowBackground](../izoomobject/get_showbackground/)() | يحصل على القيمة التي تحدد ما إذا كان Zoom سيستخدم خلفية الشريحة الهدف. قراءة **bool**. القيمة الافتراضية: true |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | يعيد الشريحة الأساسية. قراءة فقط [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_TargetSection](./get_targetsection/)() | يحصل على كائن القسم الذي يرتبط به كائن Zoom [Section](../section/). اقرأ [ISection](../isection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | يعيد كائن [ThreeDFormat](../threedformat/) الذي يحتوي على خصائص تنسيق الخط لشكل. قراءة فقط [IThreeDFormat](../ithreedformat/). |
| virtual **float** [get_TransitionDuration](../izoomobject/get_transitionduration/)() | يحصل على مدة الانتقال بين Zoom والشريحة. قراءة **float**. القيمة الافتراضية: 1.0f |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | يعيد معرفًا داخليًا يقتصر على العرض التقديمي مخصص للاستخدام من قبل الإضافات أو الكود الآخر. نظرًا لأنه يمكن أن يعاد تعيينه من قبل المستخدم أو برمجيًا، يجب عدم اعتباره مفتاحًا فريدًا دائمًا. قراءة فقط **uint32_t**. انظر أيضًا [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../ishape/get_width/)() | يحصل على عرض الشكل، مقاسًا بالنقاط. قراءة **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | يحصل على إحداثي x للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. قراءة **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | يحصل على إحداثي y للزاوية العلوية اليسرى للشكل، مقاسًا بالنقط. قراءة **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../izoomobject/get_zoomimage/)() | يحصل على الصورة لكائن Zoom. اقرأ [IPPImage](../ippimage/). |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | يعيد موضع الشكل في ترتيب z. Shapes[0] يعيد الشكل الموجود في الخلفية من ترتيب z، و Shapes[Shapes.Count - 1] يعيد الشكل الموجود في المقدمة. قراءة فقط **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | يعيد شكل عنصر نائب أساسي (شكل من التخطيط أو الشريحة الرئيسية التي يُورث منها الشكل الحالي). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عدّاد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | يعيد صورة مصغرة للشكل. نوع حدود الصورة المصغرة [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) يُستخدم افتراضيًا. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | يعيد صورة مصغرة للشكل. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. تماثل عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل تعليمة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | يخلق كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيء فعليًا، فقط يهيئ كائنًا جديدًا ويُمكّن إنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيء فعليًا، فقط يهيئ كائنًا جديدًا ويُمكّن إنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | يضبط النص البديل المرتبط بشكل. كتابة [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | يضبط عنوان النص البديل المرتبط بشكل. كتابة [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | تحدد الخاصية كيف سيُعرض الشكل في وضع الأبيض والأسود. كتابة [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | يضبط خصائص إطار الشكل. كتابة [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | يضبط ارتفاع الشكل، مقاسًا بالنقاط. كتابة **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | يحدد ما إذا كان الشكل مخفيًا. كتابة **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | يضبط الارتباط التشعبي المحدد للنقر بالفأرة. كتابة [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | يضبط الارتباط التشعبي المحدد عند مرور الفأرة. كتابة [IHyperlink](../ihyperlink/). |
| virtual void [set_ImageType](../izoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) | يضبط نوع الصورة لكائن Zoom. كتابة [ZoomImageType](../zoomimagetype/). القيمة الافتراضية: Preview |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | يضبط خيار 'Mark as decorative' للقراءة/الكتابة **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | يضبط اسم الشكل. كتابة [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | يضبط خصائص إطار الشكل الخام. كتابة [IShapeFrame](../ishapeframe/). |
| virtual void [set_ReturnToParent](../izoomobject/set_returntoparent/)(**bool**) | يضبط سلوك التنقل في عرض الشرائح. كتابة **bool**. القيمة الافتراضية: false |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | يضبط عدد الدرجات التي يدور فيها الشكل المحدد حول محور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ والسالبة إلى عكسها. كتابة **float**. |
| virtual void [set_ShowBackground](../izoomobject/set_showbackground/)(**bool**) | يضبط القيمة التي تحدد ما إذا كان Zoom سيستخدم خلفية الشريحة الهدف. كتابة **bool**. القيمة الافتراضية: true |
| virtual void [set_TargetSection](./set_targetsection/)([System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) | يضبط كائن القسم الذي يرتبط به كائن Zoom [Section](../section/). كتابة [ISection](../isection/). |
| virtual void [set_TransitionDuration](../izoomobject/set_transitionduration/)(**float**) | يضبط مدة الانتقال بين Zoom والشريحة. كتابة **float**. القيمة الافتراضية: 1.0f |
| virtual void [set_Width](../ishape/set_width/)(**float**) | يضبط عرض الشكل، مقاسًا بالنقاط. كتابة **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | يضبط إحداثي x للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. كتابة **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | يضبط إحداثي y للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. كتابة **float**. |
| virtual void [set_ZoomImage](../izoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) | يضبط الصورة لكائن Zoom. كتابة [IPPImage](../ippimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي الـ n'th كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعدد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ بل استخدم مؤشرات ذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص عدّاد المرجع المشترك ويعيده. لا يجب استدعاؤه مباشرة؛ بل استخدم مؤشرات ذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل تعليمة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ بل استخدم مؤشرات ذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عدّاد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ بل استخدم مؤشرات ذكية أو ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | يحفظ محتوى [Shape](../shape/) كملف SVG. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | يحفظ محتوى [Shape](../shape/) كملف SVG. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* فئة [IZoomObject](../izoomobject/)
* مساحة الاسم [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)