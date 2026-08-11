---
title: Shape
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides لـ C++
description: يمثل شكلاً على شريحة.
type: docs
weight: 5084
url: /ar/aspose.slides/shape/
---
## فئة Shape

يمثل شكلاً على شريحة.

```cpp
class Shape : public virtual Aspose::Slides::IShape,
              public Aspose::Slides::IDOMObject
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](./addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | يضيف عنصر نائب جديد إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى عنصر محدد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بطريقة C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بطريقة C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة نقطية بأسلوب C# حيث يتم اعتبار NaNين متساويين على الرغم من أن وفقًا لـ IEC 60559:1989 فإن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة نقطية بأسلوب C# حيث يتم اعتبار NaNين متساويين على الرغم من أن وفقًا لـ IEC 60559:1989 فإن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::String](../../system/string/) [get_AlternativeText](./get_alternativetext/)() override | يعيد النص البديل المرتبط بالشكل. اقرأ [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](./get_alternativetexttitle/)() override | يعيد عنوان النص البديل المرتبط بالشكل. اقرأ [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](./get_blackwhitemode/)() override | الخاصية تحدد كيف سيعرض الشكل في وضع العرض بالأبيض والأسود. اقرأ [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](./get_connectionsitecount/)() override | يعيد عدد مواقع الاتصال على الشكل. للقراءة فقط **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() override | يعيد البيانات المخصصة للشكل. للقراءة فقط [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() override | يعيد كائن [EffectFormat](../effectformat/) الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. ملاحظة: قد يعيد null لأنواع معينة من الأشكال التي لا تملك خصائص تأثير. للقراءة فقط [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | يعيد كائن [FillFormat](../fillformat/) الذي يحتوي على خصائص تنسيق التعبئة للشكل. ملاحظة: قد يعيد null لأنواع معينة من الأشكال التي لا تملك خصائص تعبئة. للقراءة فقط [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](./get_frame/)() override | يعيد خصائص إطار الشكل. اقرأ [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](./get_height/)() override | يحصل على ارتفاع الشكل، مقاسًا بالنقاط. اقرأ **float**. |
| **bool** [get_Hidden](./get_hidden/)() override | يحدد ما إذا كان الشكل مخفيًا. اقرأ **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() override | يعيد الارتباط التشعبي المعرفة للنقر بالفأرة. اقرأ [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](./get_hyperlinkmanager/)() override | يعيد مدير الارتباط التشعبي. للقراءة فقط [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() override | يعيد الارتباط التشعبي المعرفة لتقريب الفأرة. اقرأ [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](./get_isdecorative/)() override | يحصل على خيار 'وضع علامة كديكوري' للقراءة/الكتابة **bool**. |
| **bool** [get_IsGrouped](./get_isgrouped/)() override | يحدد ما إذا كان الشكل مجموعة. للقراءة فقط **bool**. |
| **bool** [get_IsTextHolder](./get_istextholder/)() override | يحدد ما إذا كان الشكل TextHolder_PPT. للقراءة فقط **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() override | يعيد كائن [LineFormat](../lineformat/) الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: قد يعيد null لأنواع معينة من الأشكال التي لا تملك خصائص خط. للقراءة فقط [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](./get_name/)() override | يعيد اسم الشكل. يجب ألا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. اقرأ [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](./get_officeinteropshapeid/)() override | يعيد معرفًا فريدًا على مستوى الشريحة يبقى ثابتًا طوال عمر الشكل ويتيح لبرنامج PowerPoint أو كود التفاعل الإشارة إلى الشكل من أي مكان في المستند. للقراءة فقط **uint32_t**. انظر أيضًا [Shape::get_UniqueId](./get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](./get_parentgroup/)() override | يعيد كائن [GroupShape](../groupshape/) الأب إذا كان الشكل مجموعة. وإلا يعيد null. للقراءة فقط [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](./get_placeholder/)() override | يعيد العنصر النائب للشكل. يعيد null إذا لم يكن للشكل عنصر نائب. للقراءة فقط [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | يعيد عرض الشرائح الأب للشرائح. للقراءة فقط [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](./get_rawframe/)() override | يعيد خصائص إطار الشكل الخام. اقرأ [IShapeFrame](../ishapeframe/). |
| **float** [get_Rotation](./get_rotation/)() override | يعيد عدد الدرجات التي يدور فيها الشكل المحدد حول المحور z. القيمة الموجبة تشير إلى دوران مع توقع عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه عقارب الساعة. اقرأ **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](./get_shapelock/)() override | يعيد أقفال الشكل. للقراءة فقط [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | يعيد الشريحة الأم للشكل. للقراءة فقط [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() override | يعيد كائن [ThreeDFormat](../threedformat/) الذي يحتوي على خصائص التأثير ثلاثي الأبعاد للشكل. ملاحظة: قد يعيد null لأنواع معينة من الأشكال التي لا تملك خصائص ثلاثية الأبعاد. للقراءة فقط [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](./get_uniqueid/)() override | يعيد معرفًا داخليًا على مستوى العرض مخصصًا للاستخدام من قبل الإضافات أو الكود الآخر. نظرًا لأنه يمكن إعادة تعيين هذه القيمة من قبل المستخدم أو برمجيًا، لا ينبغي اعتبارها مفتاحًا فريدًا دائمًا. للقراءة فقط **uint32_t**. انظر أيضًا [Shape::get_OfficeInteropShapeId](./get_officeinteropshapeid/). |
| **float** [get_Width](./get_width/)() override | يحصل على عرض الشكل، مقاسًا بالنقاط. اقرأ **float**. |
| **float** [get_X](./get_x/)() override | يحصل على الإحداثي x للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. اقرأ **float**. |
| **float** [get_Y](./get_y/)() override | يحصل على الإحداثي y للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. اقرأ **float**. |
| **int32_t** [get_ZOrderPosition](./get_zorderposition/)() override | يعيد موضع الشكل في ترتيب z. Shapes[0] يعيد الشكل في الخلفية، و Shapes[Shapes.Count - 1] يعيد الشكل في المقدمة. للقراءة فقط **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](./getbaseplaceholder/)() override | يعيد شكل عنصر نائب أساسي (شكل من التخطيط و/أو شريحة الماستر التي يرث منها الشكل الحالي). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)() override | يعيد صورة مصغرة للشكل. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) نوع حدود الصورة المصغرة للشكل يُستخدم بشكل افتراضي. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | يعيد صورة مصغرة للشكل. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل نداء C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](./getvisualbounds/)() | يحصل على الحدود البصرية للشكل المحسوبة من محتواه المظهر. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق ما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. تماثل عامل 'is' في C#. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | مُنشئ نسخ. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات المشتقة. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات المشتقة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع قيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [RemovePlaceholder](./removeplaceholder/)() override | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| void [set_AlternativeText](./set_alternativetext/)([System::String](../../system/string/)) override | يضبط النص البديل المرتبط بالشكل. اكتب [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](./set_alternativetexttitle/)([System::String](../../system/string/)) override | يضبط عنوان النص البديل المرتبط بالشكل. اكتب [System::String](../../system/string/). |
| void [set_BlackWhiteMode](./set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | الخاصية تحدد كيف سيعرض الشكل في وضع العرض بالأبيض والأسود. اكتب [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](./set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | يضبط خصائص إطار الشكل. اكتب [IShapeFrame](../ishapeframe/). |
| void [set_Height](./set_height/)(**float**) override | يضبط ارتفاع الشكل، مقاسًا بالنقاط. اكتب **float**. |
| void [set_Hidden](./set_hidden/)(**bool**) override | يحدد ما إذا كان الشكل مخفيًا. اكتب **bool**. |
| void [set_HyperlinkClick](./set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | يضبط الارتباط التشعبي المعرفة للنقر بالفأرة. اكتب [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](./set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | يضبط الارتباط التشعبي المعرفة لتقريب الفأرة. اكتب [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](./set_isdecorative/)(**bool**) override | يضبط خيار 'وضع علامة كديكوري' للقراءة/الكتابة **bool**. |
| void [set_Name](./set_name/)([System::String](../../system/string/)) override | يضبط اسم الشكل. يجب ألا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. اكتب [System::String](../../system/string/). |
| void [set_RawFrame](./set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | يضبط خصائص إطار الشكل الخام. اكتب [IShapeFrame](../ishapeframe/). |
| void [set_Rotation](./set_rotation/)(**float**) override | يضبط عدد الدرجات التي يدور فيها الشكل المحدد حول المحور z. القيمة الموجبة تشير إلى دوران مع توقع عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه عقارب الساعة. اكتب **float**. |
| void [set_Width](./set_width/)(**float**) override | يضبط عرض الشكل، مقاسًا بالنقاط. اكتب **float**. |
| void [set_X](./set_x/)(**float**) override | يضبط الإحداثي x للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. اكتب **float**. |
| void [set_Y](./set_y/)(**float**) override | يضبط الإحداثي y للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. اكتب **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الحجة n من القالب إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتغيير المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عداد المرجع المشترك ويعيده. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | يحفظ محتوى [Shape](./) كملف SVG. |
| void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | يحفظ محتوى [Shape](./) كملف SVG. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [IShape](../ishape/)
* الفئة [IDOMObject](../idomobject/)
* مساحة الأسماء [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)