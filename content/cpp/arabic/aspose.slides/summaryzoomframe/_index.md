---
title: SummaryZoomFrame
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل كائن Summary Zoom في شريحة.
type: docs
weight: 5318
url: /ar/aspose.slides/summaryzoomframe/
---
## SummaryZoomFrame فئة

Represents a Summary Zoom object in a slide.

```cpp
class SummaryZoomFrame : public Aspose::Slides::GraphicalObject,
                         public Aspose::Slides::ISummaryZoomFrame
```

## طرق

| طريقة | الوصف |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | يضيف عنصر نائب جديد إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُ considered قيمة NaNين متساويتين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُ considered قيمتا NaN متساويتين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | يعيد النص البديل المرتبط بشكل. اقرأ [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | يعيد عنوان النص البديل المرتبط بشكل. اقرأ [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | تحدد الخاصية كيفية عرض الشكل في وضع اللونين أبيض/أسود. اقرأ [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | يعيد عدد مواقع الاتصال على الشكل. للقراءة فقط **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | يعيد البيانات المخصصة للشكل. للقراءة فقط [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | يعيد كائن [EffectFormat](../effectformat/) الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. ملاحظة: قد يرجع null لبعض أنواع الأشكال التي لا تملك خصائص تأثير. للقراءة فقط [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | يعيد كائن [FillFormat](../fillformat/) الذي يحتوي على خصائص تنسيق التعبئة للشكل. ملاحظة: قد يرجع null لبعض أنواع الأشكال التي لا تملك خصائص تعبئة. للقراءة فقط [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | يعيد خصائص إطار الشكل. اقرأ [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | يعيد أقفال الشكل. للقراءة فقط [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | يحصل على ارتفاع الشكل، مقاسًا بالنقاط. اقرأ **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | يحدد ما إذا كان الشكل مخفيًا. اقرأ **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | يعيد الارتباط التشعبي المحدد للنقر بالماوس. اقرأ [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | يعيد مدير الارتباط التشعبي. للقراءة فقط [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | يعيد الارتباط التشعبي المحدد عند مرور الماوس. اقرأ [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | يحصل على خيار 'تعليم كزخرفة' قراءة/كتابة **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | يحدد ما إذا كان الشكل مجمعًا. للقراءة فقط **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | يحدد ما إذا كان الشكل TextHolder_PPT. للقراءة فقط **bool**. |
| [ZoomLayout](../zoomlayout/) [get_Layout](./get_layout/)() override | يحصل على تخطيط أقسام التكبير الموجز في الإطار. القيمة الافتراضية هي GridLayout. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | يعيد كائن [LineFormat](../lineformat/) الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: قد يرجع null لبعض أنواع الأشكال التي لا تملك خصائص خط. للقراءة فقط [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | يعيد اسم الشكل. يجب أن لا يكون null. استخدم قيمة سلسلة فارغة إذا لزم الأمر. اقرأ [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | يعيد معرفًا فريدًا محدودًا بالشفافية يبقى ثابتًا طوال عمر الشكل ويسمح لبرنامج PowerPoint أو شفرة التفاعل بالإشارة إلى الشكل بثقة من أي مكان في المستند. للقراءة فقط **uint32_t**. راجع أيضًا [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | يعيد كائن [GroupShape](../groupshape/) الأب إذا كان الشكل مجمعًا. وإلا يعيد null. للقراءة فقط [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | يعيد العنصر النائب للشكل. يعيد null إذا لم يكن للشكل عنصر نائب. للقراءة فقط [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | يعيد العرض الأب للشريحة. للقراءة فقط [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | يعيد خصائص إطار الشكل الخام. اقرأ [IShapeFrame](../ishapeframe/). |
| **float** [get_Rotation](../shape/get_rotation/)() override | يعيد عدد درجات دوران الشكل المحدد حول المحور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس عقارب الساعة. اقرأ **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | يعيد أقفال الشكل. للقراءة فقط [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | يعيد الشريحة الأم للشكل. للقراءة فقط [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISummaryZoomSectionCollection](../isummaryzoomsectioncollection/)\> [get_SummaryZoomCollection](./get_summaryzoomcollection/)() override | يحصل على [ISummaryZoomSectionCollection](../isummaryzoomsectioncollection/) لكائن إطار التكبير الموجز. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISummaryZoomSection](../isummaryzoomsection/)\> [get_SummaryZoomSection](./get_summaryzoomsection/)(**int32_t**) override | يعيد كائن [Section](../section/) للتكبير الموجز في الشريحة عند الفهرس المحدد. للقراءة فقط [Aspose::Slides::ISummaryZoomSection](../isummaryzoomsection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | يعيد كائن [ThreeDFormat](../threedformat/) الذي يحتوي على خصائص التأثير ثلاثي الأبعاد للشكل. ملاحظة: قد يرجع null لبعض أنواع الأشكال التي لا تملك خصائص ثلاثية الأبعاد. للقراءة فقط [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | يعيد معرفًا داخليًا محدودًا بالعرض مخصصًا لاستخدام الإضافات أو شفرة أخرى. نظرًا لأنه يمكن إعادة تعيين هذه القيمة من قبل المستخدم أو برمجيًا، يجب عدم اعتبارها مفتاحًا فريدًا دائمًا. للقراءة فقط **uint32_t**. راجع أيضًا [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | يحصل على عرض الشكل، مقاسًا بالنقاط. اقرأ **float**. |
| **float** [get_X](../shape/get_x/)() override | يحصل على إحداثي x للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. اقرأ **float**. |
| **float** [get_Y](../shape/get_y/)() override | يحصل على إحداثي y للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. اقرأ **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | يعيد موضع الشكل في ترتيب z. Shapes[0] يرجع الشكل في مؤخرة ترتيب z، وShapes[Shapes.Count - 1] يرجع الشكل في مقدمة ترتيب z. للقراءة فقط **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | يعيد شكل عنصر نائب أساسي (شكل من التخطيط و/أو الشريحة الرئيسية التي يرث منها الشكل الحالي). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المراجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | يعيد صورة مصغرة للشكل. نوع حدود الصورة المصغرة للشكل [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) يُستخدم افتراضيًا. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | يعيد صورة مصغرة للشكل. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | يحصل على الحدود البصرية للشكل المحسوبة من محتواه المعروض. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. تناظر لمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | تنفيذ عملية القفل وفق بيان C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيء جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيء كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيء كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع قيمى بـ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد المرجع المشترك بالقيمة المحددة. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | يضبط النص البديل المرتبط بشكل. كتابة [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | يضبط عنوان النص البديل المرتبط بشكل. كتابة [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | تحدد الخاصية كيفية عرض الشكل في وضع اللونين أبيض/أسود. كتابة [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | يضبط خصائص إطار الشكل. كتابة [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | يضبط ارتفاع الشكل، مقاسًا بالنقاط. كتابة **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | يحدد ما إذا كان الشكل مخفيًا. كتابة **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | يضبط الارتباط التشعبي المحدد للنقر بالماوس. كتابة [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | يضبط الارتباط التشعبي المحدد عند مرور الماوس. كتابة [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | يضبط خيار 'تعليم كزخرفة' قراءة/كتابة **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | يضبط اسم الشكل. يجب ألا يكون null. استخدم قيمة سلسلة فارغة إذا لزم الأمر. كتابة [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | يضبط خصائص إطار الشكل الخام. كتابة [IShapeFrame](../ishapeframe/). |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | يضبط عدد درجات دوران الشكل المحدد حول المحور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس عقارب الساعة. كتابة **float**. |
| void [set_Width](../shape/set_width/)(**float**) override | يضبط عرض الشكل، مقاسًا بالنقاط. كتابة **float**. |
| void [set_X](../shape/set_x/)(**float**) override | يضبط إحداثي x للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. كتابة **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | يضبط إحداثي y للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط. كتابة **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتبديل الإشارات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تناظر طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | تنفيذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | تنفيذ إلغاء القفل وفق بيان C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | يحفظ محتوى [Shape](../shape/) كملف SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | يحفظ محتوى [Shape](../shape/) كملف SVG. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* فئة [GraphicalObject](../graphicalobject/)
* فئة [ISummaryZoomFrame](../isummaryzoomframe/)
* مساحة الاسم [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)