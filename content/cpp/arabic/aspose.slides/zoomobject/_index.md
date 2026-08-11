---
title: ZoomObject
second_title: مرجع API Aspose.Slides للـ C++
description: يمثل كائن Zoom في شريحة.
type: docs
weight: 5591
url: /ar/aspose.slides/zoomobject/
---
## فئة ZoomObject

يمثل كائن Zoom في شريحة.

```cpp
class ZoomObject : public Aspose::Slides::GraphicalObject,
                   public virtual Aspose::Slides::IZoomObject
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | يضيف عنصر نائب جديد إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى عنصر محدد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالة C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يقوم بتقليد مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 ينص على أن NaN ليس مساوٍ لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يقوم بتقليد مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 ينص على أن NaN ليس مساوٍ لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | يرجع النص البديل المرتبط بشكّل. اقرأ [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | يرجع عنوان النص البديل المرتبط بشكّل. اقرأ [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | تحدد الخاصية كيفية عرض الشكّل في وضع العرض بالأبيض والأسود. اقرأ [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | يرجع عدد نقاط الاتصال على الشكّل. للقراءة فقط **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | يرجع البيانات المخصصة للشكّل. للقراءة فقط [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | يرجع كائن [EffectFormat](../effectformat/) الذي يحتوي على تأثيرات البكسل المطبقة على الشكّل. ملاحظة: قد يُعيد null لبعض أنواع الشكّل التي لا تمتلك خصائص التأثير. للقراءة فقط [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | يرجع كائن [FillFormat](../fillformat/) الذي يحتوي على خصائص تنسيق التعبئة للشكّل. ملاحظة: قد يُعيد null لبعض أنواع الشكّل التي لا تمتلك خصائص تعبئة. للقراءة فقط [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | يرجع خصائص إطار الشكّل. اقرأ [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | يرجع أقفال الشكّل. للقراءة فقط [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | يحصل على ارتفاع الشكّل، مقاسًا بالنقاط. اقرأ **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | يحدد ما إذا كان الشكّل مخفيًا. اقرأ **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | يرجع الارتباط التشعبي المحدد للنقر بالفأرة. اقرأ [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | يرجع مدير الارتباط التشعبي. للقراءة فقط [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | يرجع الارتباط التشعبي المحدد للتعامل مع مرور الفأرة. اقرأ [IHyperlink](../ihyperlink/). |
| [ZoomImageType](../zoomimagetype/) [get_ImageType](./get_imagetype/)() override | يحصل على نوع الصورة لكائن Zoom. اقرأ [ZoomImageType](../zoomimagetype/). القيمة الافتراضية: Preview |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | يحصل على خيار 'Mark as decorative'. قراءة/كتابة **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | يحدد ما إذا كان الشكّل مجمعًا. للقراءة فقط **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | يحدد ما إذا كان الشكّل هو TextHolder_PPT. للقراءة فقط **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | يرجع كائن [LineFormat](../lineformat/) الذي يحتوي على خصائص تنسيق الخط للشكّل. ملاحظة: قد يُعيد null لبعض أنواع الشكّل التي لا تمتلك خصائص خط. للقراءة فقط [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | يرجع اسم الشكّل. يجب ألا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. اقرأ [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | يرجع معرفًا فريدًا نطاقه الشريحة يبقى ثابتًا طوال عمر الشكّل ويسمح لـ PowerPoint أو كود التفاعلية بالإشارة إلى الشكّل من أي مكان في المستند. للقراءة فقط **uint32_t**. انظر أيضًا [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | يرجع كائن [GroupShape](../groupshape/) الأصل إذا كان الشكّل مجمعًا. وإلا يُعيد null. للقراءة فقط [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | يرجع العنصر النائب للشكّل. يُعيد null إذا لم يكن للشكّل عنصر نائب. للقراءة فقط [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | يرجع العرض الأب للشريحة. للقراءة فقط [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | يرجع خصائص إطار الشكّل الخام. اقرأ [IShapeFrame](../ishapeframe/). |
| **bool** [get_ReturnToParent](./get_returntoparent/)() override | يحصل على سلوك التنقل في عرض الشرائح. اقرأ **bool**. القيمة الافتراضية: false |
| **float** [get_Rotation](../shape/get_rotation/)() override | يرجع عدد الدرجات التي يدور بها الشكّل المحدد حول المحور z. تشير القيمة الموجبة إلى دوران باتجاه عقارب الساعة؛ وتشير القيمة السالبة إلى دوران عكس اتجاه العقارب. اقرأ **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | يرجع أقفال الشكّل. للقراءة فقط [IBaseShapeLock](../ibaseshapelock/). |
| **bool** [get_ShowBackground](./get_showbackground/)() override | يحصل على القيمة التي تحدد ما إذا كان Zoom سيستخدم خلفية الشريحة الوجهة. اقرأ **bool**. القيمة الافتراضية: true |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | يرجع الشريحة الأم للشكّل. للقراءة فقط [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | يرجع كائن [ThreeDFormat](../threedformat/) الذي يحتوي على خصائص التأثير ثلاثي الأبعاد للشكّل. ملاحظة: قد يُعيد null لبعض أنواع الشكّل التي لا تمتلك خصائص ثلاثية الأبعاد. للقراءة فقط [IThreeDFormat](../ithreedformat/). |
| **float** [get_TransitionDuration](./get_transitionduration/)() override | يحصل على مدة الانتقال بين Zoom والشريحة. اقرأ **float**. القيمة الافتراضية: 1.0f |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | يرجع معرفًا داخليًا نطاقه العرض مخصص للاستخدام من قبل الإضافات أو كود آخر. نظرًا لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، لا يجب اعتبارها مفتاحًا فريدًا دائمًا. للقراءة فقط **uint32_t**. انظر أيضًا [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | يحصل على عرض الشكّل، مقاسًا بالنقاط. اقرأ **float**. |
| **float** [get_X](../shape/get_x/)() override | يحصل على إحداثي x للزاوية العليا اليسرى للشكّل، مقاسًا بالنقاط. اقرأ **float**. |
| **float** [get_Y](../shape/get_y/)() override | يحصل على إحداثي y للزاوية العليا اليسرى للشكّل، مقاسًا بالنقاط. اقرأ **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](./get_zoomimage/)() override | يحصل على الصورة لكائن Zoom. اقرأ [IPPImage](../ippimage/). |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | يرجع موضع الشكّل في ترتيب z. Shapes[0] يُعيد الشكّل في الخلفية، وShapes[Shapes.Count - 1] يُعيد الشكّل في المقدمة. للقراءة فقط **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | يرجع شكل عنصر نائب أساسي (شكل من التخطيط و/أو شريحة الماستر التي يرث منها الشكل الحالي). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يُتيح تجزئة الكائنات المخصصة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | يرجع صورة مصغرة للشكّل. يستخدم النوع [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) لحدود الصورة المصغرة للشكّل كافتراضي. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | يرجع صورة مصغرة للشكّل. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | يحصل على الحدود البصرية للشكّل المحسوبة من محتواه المرسوم. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. تناظر عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يطبق قفل العبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يُتيح استنساخ الأنواع المخصصة. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويُتيح نسخ إنشاء الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | معامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويُتيح نسخ إنشاء الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدد مرات الإشارة المشتركة بالقيمة المحددة. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | يحدد أن هذا الشكّل ليس عنصرًا نائبًا. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | يضبط النص البديل المرتبط بشكّل. اكتب [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | يضبط عنوان النص البديل المرتبط بشكّل. اكتب [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | تحدد الخاصية كيفية عرض الشكّل في وضع العرض بالأبيض والأسود. اكتب [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | يضبط خصائص إطار الشكّل. اكتب [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | يضبط ارتفاع الشكّل، مقاسًا بالنقاط. اكتب **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | يضبط ما إذا كان الشكّل مخفيًا. اكتب **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | يضبط الارتباط التشعبي للنقر بالفأرة. اكتب [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | يضبط الارتباط التشعبي عند مرور الفأرة. اكتب [IHyperlink](../ihyperlink/). |
| void [set_ImageType](./set_imagetype/)([ZoomImageType](../zoomimagetype/)) override | يضبط نوع صورة كائن Zoom. اكتب [ZoomImageType](../zoomimagetype/). القيمة الافتراضية: Preview |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | يضبط خيار 'Mark as decorative'. قراءة/كتابة **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | يضبط اسم الشكّل. يجب ألا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. اكتب [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | يضبط خصائص إطار الشكّل الخام. اكتب [IShapeFrame](../ishapeframe/). |
| void [set_ReturnToParent](./set_returntoparent/)(**bool**) override | يضبط سلوك التنقل في عرض الشرائح. اكتب **bool**. القيمة الافتراضية: false |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | يضبط عدد الدرجات التي يدور بها الشكّل حول المحور z. القيمة الموجبة تعني دوران باتجاه عقارب الساعة؛ السالبة تعني عكس ذلك. اكتب **float**. |
| void [set_ShowBackground](./set_showbackground/)(**bool**) override | يضبط القيمة التي تحدد ما إذا كان Zoom سيستخدم خلفية الشريحة الوجهة. اكتب **bool**. القيمة الافتراضية: true |
| void [set_TransitionDuration](./set_transitionduration/)(**float**) override | يضبط مدة الانتقال بين Zoom والشريحة. اكتب **float**. القيمة الافتراضية: 1.0f |
| void [set_Width](../shape/set_width/)(**float**) override | يضبط عرض الشكّل، مقاسًا بالنقاط. اكتب **float**. |
| void [set_X](../shape/set_x/)(**float**) override | يضبط إحداثي x للزاوية العليا اليسرى للشكّل، مقاسًا بالنقاط. اكتب **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | يضبط إحداثي y للزاوية العليا اليسرى للشكّل، مقاسًا بالنقاط. اكتب **float**. |
| void [set_ZoomImage](./set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | يضبط الصورة لكائن Zoom. اكتب [IPPImage](../ippimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط معامل القالب رقم n كإشارة ضعيفة (بدلاً من مشاركة). يسمح بتبديل الإشارات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدد مرات الإشارة المشتركة. لا يجب استدعاؤه مباشرة؛ استخدم المراجع الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عدد مرات الإشارة المشتركة ويُعيده. لا يجب استدعاؤه مباشرة؛ استخدم المراجع الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تناظر طريقة C# [Object.ToString()](../../system/object/tostring/). يُتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يطبق بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يطبق فك قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدد مرات الإشارة الضعيفة. لا يجب استدعاؤه مباشرة؛ استخدم المراجع الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدد مرات الإشارة الضعيفة. لا يجب استدعاؤه مباشرة؛ استخدم المراجع الذكية أو ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | يحفظ محتوى [Shape](../shape/) كملف SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | يحفظ محتوى [Shape](../shape/) كملف SVG. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |
## انظر أيضًا

* فئة [GraphicalObject](../graphicalobject/)
* فئة [IZoomObject](../izoomobject/)
* مساحة الاسم [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)