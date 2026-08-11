---
title: Ink
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل كائن حبر على شريحة.
type: docs
weight: 53
url: /ar/aspose.slides.ink/ink/
---
## فئة Ink

يمثل كائن حبر على شريحة.

```cpp
class Ink : public Aspose::Slides::GraphicalObject,
            public Aspose::Slides::Ink::IInk
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) override | يضيف عنصر نائب جديد إذا لم يكن موجودًا ويعيّن خصائص العنصر النائب إلى عنصر محدد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين رغم أنه وفقًا لـ IEC 60559:1989 فإن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين رغم أنه وفقًا لـ IEC 60559:1989 فإن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/shape/get_alternativetext/)() override | يعيد النص البديل المرتبط بشكل. اقرأ [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/shape/get_alternativetexttitle/)() override | يعيد عنوان النص البديل المرتبط بشكل. اقرأ [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/shape/get_blackwhitemode/)() override | تحدد الخاصية كيفية عرض الشكل في وضع العرض بالأبيض والأسود. اقرأ [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../../aspose.slides/shape/get_connectionsitecount/)() override | يعيد عدد نقاط الاتصال على الشكل. **int32_t** للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/shape/get_customdata/)() override | يعيد البيانات المخصصة للشكل. [ICustomData](../../aspose.slides/icustomdata/) للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/shape/get_effectformat/)() override | يعيد كائن [EffectFormat](../../aspose.slides/effectformat/) الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. ملاحظة: قد يعيد null لبعض أنواع الأشكال التي لا تملك خصائص تأثير. [IEffectFormat](../../aspose.slides/ieffectformat/) للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/shape/get_fillformat/)() override | يعيد كائن [FillFormat](../../aspose.slides/fillformat/) الذي يحتوي على خصائص تنسيق التعبئة للشكل. ملاحظة: قد يعيد null لبعض أنواع الأشكال التي لا تملك خصائص تعبئة. [IFillFormat](../../aspose.slides/ifillformat/) للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/shape/get_frame/)() override | يعيد خصائص إطار الشكل. اقرأ [IShapeFrame](../../aspose.slides/ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/graphicalobject/get_graphicalobjectlock/)() override | يعيد أقفال الشكل. [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/) للقراءة فقط. |
| **float** [get_Height](../../aspose.slides/shape/get_height/)() override | يحصل على ارتفاع الشكل، مقاسًا بالنقاط. **float** للقراءة. |
| **bool** [get_Hidden](../../aspose.slides/shape/get_hidden/)() override | يحدد ما إذا كان الشكل مخفيًا. **bool** للقراءة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/shape/get_hyperlinkclick/)() override | يعيد الارتباط التشعبي المحدد للنقر بالماوس. اقرأ [IHyperlink](../../aspose.slides/ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/shape/get_hyperlinkmanager/)() override | يعيد مدير الارتباط التشعبي. [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/) للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/shape/get_hyperlinkmouseover/)() override | يعيد الارتباط التشعبي المحدد للتمرير فوق الفأرة. اقرأ [IHyperlink](../../aspose.slides/ihyperlink/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[InkEffectType](../inkeffecttype/), [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\>\>\> [get_InkEffectImages](./get_inkeffectimages/)() | يحصل على مجموعة الصور المخصصة المستخدمة لمحاكاة التأثيرات البصرية لفرش الحبر. تُستخدم هذه الصور عند عرض الحبر بقيم [InkEffectType](../inkeffecttype/) محددة، مثل Galaxy، Rainbow، إلخ. من خلال توفير صورك الخاصة، يمكنك التحكم في مظهر كل تأثير حبر. |
| **bool** [get_IsDecorative](../../aspose.slides/shape/get_isdecorative/)() override | يحصل على خيار 'Mark as decorative'. قراءة/كتابة **bool**. |
| **bool** [get_IsGrouped](../../aspose.slides/shape/get_isgrouped/)() override | يحدد ما إذا كان الشكل مجموعة. **bool** للقراءة فقط. |
| **bool** [get_IsTextHolder](../../aspose.slides/shape/get_istextholder/)() override | يحدد ما إذا كان الشكل TextHolder_PPT. **bool** للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/shape/get_lineformat/)() override | يعيد كائن [LineFormat](../../aspose.slides/lineformat/) الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: قد يعيد null لبعض أنواع الأشكال التي لا تملك خصائص خط. [ILineFormat](../../aspose.slides/ilineformat/) للقراءة فقط. |
| [System::String](../../system/string/) [get_Name](../../aspose.slides/shape/get_name/)() override | يعيد اسم الشكل. يجب ألا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. اقرأ [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)() override | يعيد معرّفًا فريدًا ضمن نطاق الشريحة يظل ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو كود التفاعل بالإشارة إلى الشكل بشكل موثوق من أي مكان في المستند. **uint32_t** للقراءة فقط. انظر أيضًا [Shape::get_UniqueId](../../aspose.slides/shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/shape/get_parentgroup/)() override | يعيد كائن [GroupShape](../../aspose.slides/groupshape/) الأب إذا كان الشكل مجموعة. وإلا يعيد null. [IGroupShape](../../aspose.slides/igroupshape/) للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/shape/get_placeholder/)() override | يعيد العنصر النائب للشكل. يعيد null إذا لم يكن للشكل عنصر نائب. [IPlaceholder](../../aspose.slides/iplaceholder/) للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/shape/get_presentation/)() override | يعيد العرض الأصل للشفرة. [IPresentation](../../aspose.slides/ipresentation/) للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/shape/get_rawframe/)() override | يعيد خصائص إطار الشكل الخام. اقرأ [IShapeFrame](../../aspose.slides/ishapeframe/). |
| **float** [get_Rotation](../../aspose.slides/shape/get_rotation/)() override | يعيد عدد الدرجات التي يدور بها الشكل المحدد حول المحور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه العقارب. **float** للقراءة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/shape/get_shapelock/)() override | يعيد أقفال الشكل. [IBaseShapeLock](../../aspose.slides/ibaseshapelock/) للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/shape/get_slide/)() override | يعيد الشريحة الأب للشكل. [IBaseSlide](../../aspose.slides/ibaseslide/) للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/shape/get_threedformat/)() override | يعيد كائن [ThreeDFormat](../../aspose.slides/threedformat/) الذي يحتوي على خصائص التأثير ثلاثي الأبعاد للشكل. ملاحظة: قد يعيد null لبعض أنواع الأشكال التي لا تملك خصائص ثلاثية الأبعاد. [IThreeDFormat](../../aspose.slides/ithreedformat/) للقراءة فقط. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IInkTrace](../iinktrace/)\>\> [get_Traces](./get_traces/)() override | يحصل على جميع الآثار الموجودة في عنصر [IInk](../iink/) [IInkTrace](../iinktrace/). للقراءة فقط. |
| **uint32_t** [get_UniqueId](../../aspose.slides/shape/get_uniqueid/)() override | يعيد معرّفًا داخليًا ضمن نطاق العرض مخصصًا للاستخدام من قبل الإضافات أو الكود الآخر. نظرًا لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، لا يجب اعتبارها مفتاحًا فريدًا دائمًا. **uint32_t** للقراءة فقط. انظر أيضًا [Shape::get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/). |
| **float** [get_Width](../../aspose.slides/shape/get_width/)() override | يحصل على عرض الشكل، مقاسًا بالنقاط. **float** للقراءة. |
| **float** [get_X](../../aspose.slides/shape/get_x/)() override | يحصل على إحداثي x للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. **float** للقراءة. |
| **float** [get_Y](../../aspose.slides/shape/get_y/)() override | يحصل على إحداثي y للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. **float** للقراءة. |
| **int32_t** [get_ZOrderPosition](../../aspose.slides/shape/get_zorderposition/)() override | يعيد موضع الشكل في ترتيب z. Shapes[0] يعيد الشكل في الخلفية من ترتيب z، وShapes[Shapes.Count - 1] يعيد الشكل في المقدمة من ترتيب z. **int32_t** للقراءة فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder/)() override | يعيد شكلًا نائبًا أساسيًا (شكل من التخطيط و/أو الشريحة الأساسية التي يرث منها الشكل الحالي). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)() override | يعيد صورة مصغرة للشكل. نوع حدود الصورة المصغرة [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) يُستخدم افتراضيًا. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) override | يعيد صورة مصغرة للشكل. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../../aspose.slides/shape/getvisualbounds/)() | يحصل على الحدود البصرية للشكل محسوبة من محتواه المرسوم. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموضح بواسطة targetType. تناظر لمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ عملية القفل (lock) في C#. استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يهيء جميع هياكل البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيء كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيء كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات حسب المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات حسب المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي مع nullptr حسب المرجع. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder/)() override | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| void [set_AlternativeText](../../aspose.slides/shape/set_alternativetext/)([System::String](../../system/string/)) override | يضبط النص البديل المرتبط بالشكل. اكتب [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../../aspose.slides/shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | يضبط عنوان النص البديل المرتبط بالشكل. اكتب [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../../aspose.slides/shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) override | تحدد الخاصية كيفية عرض الشكل في وضع الأبيض والأسود. اكتب [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| void [set_Frame](../../aspose.slides/shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | يضبط خصائص إطار الشكل. اكتب [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Height](../../aspose.slides/shape/set_height/)(**float**) override | يضبط ارتفاع الشكل، مقاسًا بالنقاط. اكتب **float**. |
| void [set_Hidden](../../aspose.slides/shape/set_hidden/)(**bool**) override | يضبط ما إذا كان الشكل مخفيًا. اكتب **bool**. |
| void [set_HyperlinkClick](../../aspose.slides/shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | يضبط الارتباط التشعبي المحدد للنقر بالماوس. اكتب [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_HyperlinkMouseOver](../../aspose.slides/shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | يضبط الارتباط التشعبي المحدد للتمرير فوق الفأرة. اكتب [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_IsDecorative](../../aspose.slides/shape/set_isdecorative/)(**bool**) override | يضبط خيار 'Mark as decorative'. قراءة/كتابة **bool**. |
| void [set_Name](../../aspose.slides/shape/set_name/)([System::String](../../system/string/)) override | يضبط اسم الشكل. يجب ألا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. اكتب [System::String](../../system/string/). |
| void [set_RawFrame](../../aspose.slides/shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | يضبط خصائص إطار الشكل الخام. اكتب [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Rotation](../../aspose.slides/shape/set_rotation/)(**float**) override | يضبط عدد الدرجات التي يدور بها الشكل المحدد حول المحور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه العقارب. اكتب **float**. |
| void [set_Width](../../aspose.slides/shape/set_width/)(**float**) override | يضبط عرض الشكل، مقاسًا بالنقاط. اكتب **float**. |
| void [set_X](../../aspose.slides/shape/set_x/)(**float**) override | يضبط إحداثي x للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. اكتب **float**. |
| void [set_Y](../../aspose.slides/shape/set_y/)(**float**) override | يضبط إحداثي y للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. اكتب **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط معامل القالب الـ n'th كإشارة ضعيفة (بدلاً من مشاركة). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلًا من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلًا من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تناظر طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل (unlock) في C#. استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلًا من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلًا من ذلك. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | يحفظ محتوى [Shape](../../aspose.slides/shape/) كملف SVG. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | يحفظ محتوى [Shape](../../aspose.slides/shape/) كملف SVG. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## أنظر أيضًا

* الفئة [GraphicalObject](../../aspose.slides/graphicalobject/)
* الفئة [IInk](../iink/)
* النطاق [Aspose::Slides::Ink](../)
* المكتبة [Aspose.Slides](../../)