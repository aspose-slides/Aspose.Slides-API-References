---
title: ZoomFrame
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل كائن Zoom للشرائح داخل شريحة.
type: docs
weight: 5578
url: /ar/aspose.slides/zoomframe/
---
## فئة ZoomFrame

يمثل كائن Zoom [Slide](../slide/) في شريحة.

```cpp
class ZoomFrame : public Aspose::Slides::ZoomObject,
                  public Aspose::Slides::IZoomFrame
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN مساويتين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا تساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN مساويتين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا تساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | يرجع النص البديل المرتبط بالشكل. اقرأ [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | يرجع عنوان النص البديل المرتبط بالشكل. اقرأ [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | الخاصية تحدد كيفية عرض الشكل في وضعية الأبيض والأسود. اقرأ [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | يرجع عدد نقاط الاتصال على الشكل. **int32_t** للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | يرجع البيانات المخصصة للشكل. [ICustomData](../icustomdata/) للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | يرجع كائن [EffectFormat](../effectformat/) الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. ملاحظة: قد يرجع قيمة null لأنواع معينة من الأشكال التي لا تمتلك خصائص تأثير. [IEffectFormat](../ieffectformat/) للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | يرجع كائن [FillFormat](../fillformat/) الذي يحتوي على خصائص تنسيقات التعبئة للشكل. ملاحظة: قد يرجع قيمة null لأنواع معينة من الأشكال التي لا تمتلك خصائص تعبئة. [IFillFormat](../ifillformat/) للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | يرجع خصائص إطار الشكل. اقرأ [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | يرجع أقفال الشكل. [IGraphicalObjectLock](../igraphicalobjectlock/) للقراءة فقط. |
| **float** [get_Height](../shape/get_height/)() override | يحصل على ارتفاع الشكل، مقاسًا بالنقاط. **float** للقراءة. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | يحدد ما إذا كان الشكل مخفيًا. **bool** للقراءة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | يرجع الارتباط التشعبي المعرفة للنقر بالفأرة. اقرأ [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | يرجع مدير الارتباط التشعبي. [IHyperlinkManager](../ihyperlinkmanager/) للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | يرجع الارتباط التشعبي المحدد لتمرير الفأرة فوقه. اقرأ [IHyperlink](../ihyperlink/). |
| [ZoomImageType](../zoomimagetype/) [get_ImageType](../zoomobject/get_imagetype/)() override | يحصل على نوع الصورة لكائن Zoom. اقرأ [ZoomImageType](../zoomimagetype/). القيمة الافتراضية: Preview |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | يحصل على خيار 'تمييز كديكور'. قراءة/كتابة **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | يحدد ما إذا كان الشكل مجموعة. **bool** للقراءة فقط. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | يحدد ما إذا كان الشكل TextHolder_PPT. **bool** للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | يرجع كائن [LineFormat](../lineformat/) الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: قد يرجع قيمة null لأنواع معينة من الأشكال التي لا تمتلك خصائص خط. [ILineFormat](../ilineformat/) للقراءة فقط. |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | يرجع اسم الشكل. يجب ألا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. اقرأ [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | يرجع معرفًا فريدًا يخص الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لبرنامج PowerPoint أو كود التفاعل بالإشارة إلى الشكل من أي مكان في المستند. **uint32_t** للقراءة فقط. انظر أيضًا [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | يرجع كائن [GroupShape](../groupshape/) الأب إذا كان الشكل مجموعة. وإلا يرجع null. [IGroupShape](../igroupshape/) للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | يرجع العنصر النائب للشكل. يرجع null إذا لم يكن للشكل عنصر نائب. [IPlaceholder](../iplaceholder/) للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | يرجع عرض الشرائح الأب للشريحة. [IPresentation](../ipresentation/) للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | يرجع خصائص إطار الشكل الخام. اقرأ [IShapeFrame](../ishapeframe/). |
| **bool** [get_ReturnToParent](../zoomobject/get_returntoparent/)() override | يحصل على سلوك التنقل في عرض الشرائح. **bool** للقراءة. القيمة الافتراضية: false |
| **float** [get_Rotation](../shape/get_rotation/)() override | يرجع عدد درجات دوران الشكل المحدد حول المحور z. القيمة الموجبة تدل على دوران باتجاه عقارب الساعة؛ القيمة السالبة تدل على دوران عكس اتجاه العقارب. **float** للقراءة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | يرجع أقفال الشكل. [IBaseShapeLock](../ibaseshapelock/) للقراءة فقط. |
| **bool** [get_ShowBackground](../zoomobject/get_showbackground/)() override | يحصل على قيمة تحدد ما إذا كان Zoom سيستخدم خلفية الشريحة الوجهة. **bool** للقراءة. القيمة الافتراضية: true |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | يرجع شريحة الأب للشكل. [IBaseSlide](../ibaseslide/) للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_TargetSlide](./get_targetslide/)() override | يحصل على كائن الشريحة الذي يربط إليه كائن Zoom [Slide](../slide/). اقرأ [ISlide](../islide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | يرجع كائن [ThreeDFormat](../threedformat/) الذي يحتوي على خصائص تأثير ثلاثي الأبعاد للشكل. ملاحظة: قد يرجع null لأنواع معينة من الأشكال التي لا تمتلك خصائص ثلاثية الأبعاد. [IThreeDFormat](../ithreedformat/) للقراءة فقط. |
| **float** [get_TransitionDuration](../zoomobject/get_transitionduration/)() override | يحصل على مدة الانتقال بين Zoom والشريحة. **float** للقراءة. القيمة الافتراضية: 1.0f |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | يرجع معرفًا داخليًا يخص العرض يُقصد به الاستخدام من قبل الإضافات أو الكود الآخر. نظرًا لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، لا يجب اعتبارها مفتاحًا فريدًا دائمًا. **uint32_t** للقراءة فقط. انظر أيضًا [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | يحصل على عرض الشكل، مقاسًا بالنقاط. **float** للقراءة. |
| **float** [get_X](../shape/get_x/)() override | يحصل على إحداثي x للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. **float** للقراءة. |
| **float** [get_Y](../shape/get_y/)() override | يحصل على إحداثي y للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. **float** للقراءة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../zoomobject/get_zoomimage/)() override | يحصل على صورة لكائن Zoom. اقرأ [IPPImage](../ippimage/). |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | يرجع موضع الشكل في ترتيب z. Shapes[0] يرجع الشكل في خلفية ترتيب z، وShapes[Shapes.Count - 1] يرجع الشكل في مقدمة ترتيب z. **int32_t** للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | يرجع شكل عنصر نائب أساسي (شكل من التخطيط و/أو الشريحة الرئيسية التي يرث منها الشكل الحالي). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة (hash) الكائنات المخصصة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | يرجع صورة مصغرة للشكل. نوع حدود الصورة المصغرة [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) يستخدم افتراضيًا. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | يرجع صورة مصغرة للشكل. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | يحصل على حدود الشكل المرئية المحسوبة من محتواه المرسوم. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. مماثل لمُعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يتهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ أي شيء فعليًا، بل يتهيئ كائنًا جديدًا ويتيح إنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يتهيئ كائنًا جديدًا ويتيح إنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | يضبط النص البديل المرتبط بالشكل. اكتب [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | يضبط عنوان النص البديل المرتبط بالشكل. اكتب [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | الخاصية تحدد كيفية عرض الشكل في وضعية الأبيض والأسود. اكتب [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | يضبط خصائص إطار الشكل. اكتب [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | يضبط ارتفاع الشكل، مقاسًا بالنقاط. اكتب **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | يحدد ما إذا كان الشكل مخفيًا. اكتب **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | يضبط الارتباط التشعبي المعرفة للنقر بالفأرة. اكتب [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | يضبط الارتباط التشعبي المعرفة لتمرير الفأرة فوقه. اكتب [IHyperlink](../ihyperlink/). |
| void [set_ImageType](../zoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) override | يضبط نوع الصورة لكائن Zoom. اكتب [ZoomImageType](../zoomimagetype/). القيمة الافتراضية: Preview |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | يضبط خيار 'تمييز كديكور'. قراءة/كتابة **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | يضبط اسم الشكل. يجب ألا يكون null. استخدم قيمة سلسلة فارغة إذا لزم الأمر. اكتب [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | يضبط خصائص إطار الشكل الخام. اكتب [IShapeFrame](../ishapeframe/). |
| void [set_ReturnToParent](../zoomobject/set_returntoparent/)(**bool**) override | يضبط سلوك التنقل في عرض الشرائح. اكتب **bool**. القيمة الافتراضية: false |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | يضبط عدد درجات دوران الشكل المحدد حول المحور z. القيمة الموجبة تدل على دوران باتجاه عقارب الساعة؛ القيمة السالبة تدل على دوران عكس الاتجاه. اكتب **float**. |
| void [set_ShowBackground](../zoomobject/set_showbackground/)(**bool**) override | يضبط القيمة التي تحدد ما إذا كان Zoom سيستخدم خلفية الشريحة الوجهة. اكتب **bool**. القيمة الافتراضية: true |
| void [set_TargetSlide](./set_targetslide/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) override | يضبط كائن الشريحة الذي يربط إليه كائن Zoom [Slide](../slide/). اكتب [ISlide](../islide/). |
| void [set_TransitionDuration](../zoomobject/set_transitionduration/)(**float**) override | يضبط مدة الانتقال بين Zoom والشريحة. اكتب **float**. القيمة الافتراضية: 1.0f |
| void [set_Width](../shape/set_width/)(**float**) override | يضبط عرض الشكل، مقاسًا بالنقاط. اكتب **float**. |
| void [set_X](../shape/set_x/)(**float**) override | يضبط إحداثي x للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. اكتب **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | يضبط إحداثي y للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. اكتب **float**. |
| void [set_ZoomImage](../zoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | يضبط صورة لكائن Zoom. اكتب [IPPImage](../ippimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط معامل القالب رقم n كمؤشر ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | يحفظ محتوى [Shape](../shape/) كملف SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | يحفظ محتوى [Shape](../shape/) كملف SVG. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* فئة [ZoomObject](../zoomobject/)
* فئة [IZoomFrame](../izoomframe/)
* نطاق [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)