---
title: ITextFrameFormat
second_title: مرجع API لـ Aspose.Slides لـ C++
description: يحتوي على خصائص تنسيق TextFrame.
type: docs
weight: 4083
url: /ar/aspose.slides/itextframeformat/
---
## ITextFrameFormat فئة

يحتوي على خصائص التنسيق الخاصة بـ [TextFrame](../textframe/).

```cpp
class ITextFrameFormat : public virtual System::Object
```

## طرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يوحِّي مقارنة النقطة العائمة بأسلوب C# حيث يتم اعتبار NaNين متساويين على الرغم من أن معيار IEC 60559:1989 يوضح أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يوحِّي مقارنة النقطة العائمة بأسلوب C# حيث يتم اعتبار NaNين متساويين على الرغم من أن معيار IEC 60559:1989 يوضح أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | يُرجع نص المرفق الرأسي في [TextFrame](../textframe/). اقرأ [TextAnchorType](../textanchortype/). |
| virtual [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() | يُرجع وضع الملء التلقائي للنص. اقرأ [TextAutofitType](../textautofittype/). |
| virtual [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() | إذا كان [NullableBool::True](../nullablebool/) فيجب أن يكون النص متمركزًا أفقياً داخل الصندوق. اقرأ [NullableBool](../nullablebool/). |
| virtual **int32_t** [get_ColumnCount](./get_columncount/)() | يُرجع عدد الأعمدة في مساحة النص. يجب أن تكون هذه القيمة رقمًا موجبًا. وإلا سيتم ضبطها إلى صفر. القيمة 0 تعني قيمة غير معرّفة. اقرأ **int32_t**. |
| virtual **double** [get_ColumnSpacing](./get_columnspacing/)() | يُرجع المسافة بين أعمدة النص في مساحة النص (بالنقاط). يجب أن ينطبق ذلك فقط عندما يكون هناك أكثر من عمود واحد. يجب أن تكون هذه القيمة رقمًا موجبًا. وإلا سيتم ضبطها إلى صفر. اقرأ **double**. |
| virtual **bool** [get_KeepTextFlat](./get_keeptextflat/)() | يُرجع أو يضبط إبقاء النص خارج المشهد ثلاثي الأبعاد تمامًا. اقرأ **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | يُرجع الهامش السفلي (بالنقاط) في [TextFrame](../textframe/). اقرأ **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | يُرجع الهامش الأيسر (بالنقاط) في [TextFrame](../textframe/). اقرأ **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | يُرجع الهامش الأيمن (بالنقاط) في [TextFrame](../textframe/). اقرأ **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | يُرجع الهامش العلوي (بالنقاط) في [TextFrame](../textframe/). اقرأ **double**. |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | يحدد الدوران المخصص المطبق على النص داخل الصندوق المحيط. إذا لم يتم تحديده، يُستخدم دوران الشكل المرافق. إذا تم تحديده، يُطبق بشكل مستقل عن الشكل. أي أن الشكل يمكن أن يكون له دوران إضافي إلى جانب دوران النص نفسه. القيمة الناتجة للدوران المرئي للنص ملخّصة من هذه الخاصية والنوع الرأسي المحدد مسبقًا في الخاصية TextVerticalType. اقرأ **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TextStyle](./get_textstyle/)() | يُرجع نمط النص. قراءة فقط [ITextStyle](../itextstyle/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | يُحدد اتجاه النص. القيمة الناتجة للدوران المرئي للنص ملخّصة من هذه الخاصية والزاوية المخصصة في الخاصية RotationAngle. اقرأ [Slides::TextVerticalType](../textverticaltype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() | يُرجع الكائن [ThreeDFormat](../threedformat/) الذي يمثل خصائص التأثير ثلاثي الأبعاد للنص. قراءة فقط [IThreeDFormat](../ithreedformat/). |
| virtual [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() | يحصل على شكل تغليف النص. اقرأ [TextShapeType](../textshapetype/). |
| virtual [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() | **True** إذا كان النص مُلتفًا على هوامش [TextFrame](../textframe/). اقرأ [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عدّاد المرجع المرتبط بالكائن. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() | يحصل على بيانات تنسيق إطار النص الفعّالة مع تطبيق الوراثة. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يُنفّذ قفل تعبير C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيء جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ أي شيء فعليًا، بل يهيء كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات المشتقة. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يهيء كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات المشتقة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بحسب المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بحسب المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدد المراجع المشتركة بالقيمة المحددة. |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) | يُعيّن نص المرفق الرأسي في [TextFrame](../textframe/). اكتب [TextAnchorType](../textanchortype/). |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) | يُعيّن وضع الملء التلقائي للنص. اكتب [TextAutofitType](../textautofittype/). |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) | إذا كان [NullableBool::True](../nullablebool/) فيجب أن يكون النص متمركزًا أفقياً داخل الصندوق. اكتب [NullableBool](../nullablebool/). |
| virtual void [set_ColumnCount](./set_columncount/)(**int32_t**) | يُعيّن عدد الأعمدة في مساحة النص. يجب أن تكون هذه القيمة رقمًا موجبًا. وإلا سيتم ضبطها إلى صفر. القيمة 0 تعني قيمة غير معرفة. اكتب **int32_t**. |
| virtual void [set_ColumnSpacing](./set_columnspacing/)(**double**) | يُعيّن المسافة بين أعمدة النص في مساحة النص (بالنقاط). يجب أن ينطبق ذلك فقط عندما يكون هناك أكثر من عمود واحد. يجب أن تكون هذه القيمة رقمًا موجبًا. وإلا سيتم ضبطها إلى صفر. اكتب **double**. |
| virtual void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) | يُرجع أو يضبط إبقاء النص خارج المشهد ثلاثي الأبعاد تمامًا. اكتب **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | يُعيّن الهامش السفلي (بالنقاط) في [TextFrame](../textframe/). اكتب **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | يُعيّن الهامش الأيسر (بالنقاط) في [TextFrame](../textframe/). اكتب **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | يُعيّن الهامش الأيمن (بالنقاط) في [TextFrame](../textframe/). اكتب **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | يُعيّن الهامش العلوي (بالنقاط) في [TextFrame](../textframe/). اكتب **double**. |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | يحدد الدوران المخصص المطبق على النص داخل الصندوق المحيط. إذا لم يتم تحديده، يُستخدم دوران الشكل المرافق. إذا تم تحديده، يُطبق بشكل مستقل عن الشكل. أي أن الشكل يمكن أن يكون له دوران إضافي إلى جانب دوران النص نفسه. القيمة الناتجة للدوران المرئي للنص ملخّصة من هذه الخاصية والنوع الرأسي المحدد مسبقًا في الخصية TextVerticalType. اكتب **float**. |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | يُحدد اتجاه النص. القيمة الناتجة للدوران المرئي للنص ملخّصة من هذه الخاصية والزاوية المخصصة في الخصية RotationAngle. اكتب [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) | يُعيّن شكل تغليف النص. اكتب [TextShapeType](../textshapetype/). |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) | **True** إذا كان النص مُلتفًا على هوامش [TextFrame](../textframe/). اكتب [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النمطي الـ n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعدد المراجع المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدد المراجع المشتركة. لا يجب استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويُرجع عدد المراجع المشتركة. لا يجب استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يُنفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يُنفّذ إلغاء قفل تعبير C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدد المراجع الضعيفة. لا يجب استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عدد المراجع الضعيفة. لا يجب استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* فئة [Object](../../system/object/)
* نطاق [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)