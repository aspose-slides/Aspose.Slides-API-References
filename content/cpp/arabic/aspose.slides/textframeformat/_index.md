---
title: TextFrameFormat
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يتضمن خصائص formatTextFrameFormatting الخاصة بـ TextFrame.
type: docs
weight: 5461
url: /ar/aspose.slides/textframeformat/
---
## فئة TextFrameFormat

يتضمن خصائص formatTextFrameFormatting الخاصة بـ [TextFrame](../textframe/).

```cpp
class TextFrameFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::ITextFrameFormat,
                        public Aspose::Slides::Charts::IChartTextBlockFormat
```

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | يقارن مع الكائن المحدد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يقلد مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 يُشير إلى أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يقلد مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 يُشير إلى أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() override | يرجع نص المرساة العمودية في [TextFrame](../textframe/). اقرء [TextAnchorType](../textanchortype/). |
| [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() override | يرجع وضع الملء التلقائي للنص. اقرء [TextAutofitType](../textautofittype/). |
| [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() override | إذا كان [NullableBool::True](../nullablebool/) يجب أن يُوسط النص في الصندوق أفقياً. اقرء [NullableBool](../nullablebool/). |
| **int32_t** [get_ColumnCount](./get_columncount/)() override | يرجع عدد الأعمدة في مساحة النص. يجب أن تكون هذه القيمة رقمًا موجبًا. وإلا سيتم ضبط القيمة على صفر. القيمة 0 تعني قيمة غير معرفة. اقرء **int32_t**. |
| **double** [get_ColumnSpacing](./get_columnspacing/)() override | يرجع المسافة بين أعمدة النص في مساحة النص (بالنقاط). يجب أن يُطبق ذلك فقط عندما يكون هناك أكثر من عمود واحد. يجب أن تكون هذه القيمة رقمًا موجبًا. وإلا سيتم ضبط القيمة على صفر. اقرء **double**. |
| **bool** [get_KeepTextFlat](./get_keeptextflat/)() override | يحصل على حفظ النص مسطحًا حتى إذا تم تطبيق تأثير دوران ثلاثي الأبعاد. اقرء **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | يرجع الهامش السفلي (بالنقاط) في [TextFrame](../textframe/). اقرء **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | يرجع الهامش الأيسر (بالنقاط) في [TextFrame](../textframe/). اقرء **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | يرجع الهامش الأيمن (بالنقاط) في [TextFrame](../textframe/). اقرء **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | يرجع الهامش العلوي (بالنقاط) في [TextFrame](../textframe/). اقرء **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | يرجع كائن Parent_Immediate. قراءة فقط [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | يرجع الأب [IPresentationComponent](../ipresentationcomponent/). قراءة فقط [IPresentationComponent](../ipresentationcomponent/). |
| **float** [get_RotationAngle](./get_rotationangle/)() override | يحدد دورانًا مخصصًا يُطبق على النص داخل صندوق الحدود. إذا لم يُحدد، يُستخدم دوران الشكل المصاحب. إذا تم تحديده، يُطبق مستقلًا عن الشكل. أي أن الشكل يمكن أن يكون له دوران بالإضافة إلى دوران النص نفسه. القيمة الناتجة لدوران النص البصري يتم تلخيصها من هذه الخاصية والنوع العمودي المحدد مسبقًا في الخاصية TextVerticalType. اقرء **float**. |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | يحدد توجه النص. القيمة الناتجة لدوران النص البصري يتم تلخيصها من هذه الخاصية والزواية المخصصة في الخاصية RotationAngle. اقرء [Slides::TextVerticalType](../textverticaltype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() override | يرجع كائن [ThreeDFormat](../threedformat/) الذي يمثل خصائص التأثير ثلاثي الأبعاد للنص. قراءة فقط [IThreeDFormat](../ithreedformat/). |
| [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() override | يحصل على شكل التفاف النص. اقرء [TextShapeType](../textshapetype/). |
| [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() override | **True** إذا كان النص مغطى عند هوامش [TextFrame](../textframe/). اقرء [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل بيانات عداد المرجع المرتبط بالكائن. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() override | يحصل على بيانات تنسيق إطار النص الفعّالة مع تطبيق الوراثة. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | يرجع رمز التجزئة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مشابه لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. مشابه لمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحرس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عدّاد المرجع المشترك بالقيمة المحددة. |
| void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) override | يضبط نص المرساة العمودية في [TextFrame](../textframe/). اكتب [TextAnchorType](../textanchortype/). |
| void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) override | يضبط وضع الملء التلقائي للنص. اكتب [TextAutofitType](../textautofittype/). |
| void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) override | إذا كان [NullableBool::True](../nullablebool/) يجب أن يُوسط النص أفقياً في الصندوق. اكتب [NullableBool](../nullablebool/). |
| void [set_ColumnCount](./set_columncount/)(**int32_t**) override | يضبط عدد الأعمدة في مساحة النص. يجب أن تكون هذه القيمة رقمًا موجبًا. وإلا سيتم ضبط القيمة على صفر. القيمة 0 تعني قيمة غير معرفة. اكتب **int32_t**. |
| void [set_ColumnSpacing](./set_columnspacing/)(**double**) override | يضبط المسافة بين أعمدة النص في مساحة النص (بالنقاط). يجب أن يُطبق ذلك فقط عندما يكون هناك أكثر من عمود واحد. يجب أن تكون هذه القيمة رقمًا موجبًا. وإلا سيتم ضبط القيمة على صفر. اكتب **double**. |
| void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) override | يضبط الحفاظ على النص مسطحًا حتى إذا تم تطبيق تأثير دوران ثلاثي الأبعاد. اكتب **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | يضبط الهامش السفلي (بالنقاط) في [TextFrame](../textframe/). اكتب **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | يضبط الهامش الأيسر (بالنقاط) في [TextFrame](../textframe/). اكتب **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | يضبط الهامش الأيمن (بالنقاط) في [TextFrame](../textframe/). اكتب **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | يضبط الهامش العلوي (بالنقاط) في [TextFrame](../textframe/). اكتب **double**. |
| void [set_RotationAngle](./set_rotationangle/)(**float**) override | يحدد دورانًا مخصصًا يُطبق على النص داخل صندوق الحدود. إذا لم يُحدد، يُستخدم دوران الشكل المصاحب. إذا تم تحديده، يُطبق مستقلًا عن الشكل. أي أن الشكل يمكن أن يكون له دوران بالإضافة إلى دوران النص نفسه. القيمة الناتجة لدوران النص البصري يتم تلخيصها من هذه الخاصية والنوع العمودي المحدد مسبقًا في الخاصية TextVerticalType. اكتب **float**. |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | يحدد توجه النص. القيمة الناتجة لدوران النص البصري يتم تلخيصها من هذه الخاصية والزواية المخصصة في الخاصية RotationAngle. اكتب [Slides::TextVerticalType](../textverticaltype/). |
| void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) override | يضبط شكل التفاف النص. اكتب [TextShapeType](../textshapetype/). |
| void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) override | **True** إذا كان النص مغطى عند هوامش [TextFrame](../textframe/). اكتب [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
|  [TextFrameFormat](./textframeformat/)() | يهيئ نسخة جديدة من الفئة [TextFrameFormat](./). |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ تركيب C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحرس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* الفئة [PVIObject](../pviobject/)
* الفئة [ITextFrameFormat](../itextframeformat/)
* الفئة [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat/)
* نطاق الاسم [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)