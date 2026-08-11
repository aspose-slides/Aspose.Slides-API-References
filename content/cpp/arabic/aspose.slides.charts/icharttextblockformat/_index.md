---
title: IChartTextBlockFormat
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل خصائص تنسيق لعناصر نص المخطط.
type: docs
weight: 885
url: /ar/aspose.slides.charts/icharttextblockformat/
---
## IChartTextBlockFormat فئة


Represents formatting properties for chart text elements.

```cpp
class IChartTextBlockFormat : public virtual System::Object
```

## الأساليب

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالة C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمة NaNين متساويتين بالرغم من أنه وفقًا لـ IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمة NaNين متساويتين بالرغم من أنه وفقًا لـ IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [TextAnchorType](../../aspose.slides/textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | يعيد النص العمودي المثبت في [TextFrame](../../aspose.slides/textframe/). قراءة [TextAnchorType](../../aspose.slides/textanchortype/). |
| virtual [TextAutofitType](../../aspose.slides/textautofittype/) [get_AutofitType](./get_autofittype/)() | يعيد وضع الملاءمة التلقائية للنص. قد يؤدي تغيير هذه الخاصية إلى تأثير معين فقط على أجزاء المخطط التالية: [DataLabel](../datalabel/) و [DataLabelFormat](../datalabelformat/) (دعم كامل في PowerPoint 2013؛ في PowerPoint 2007 لا يوجد تأثير على العرض). قراءة [TextAutofitType](../../aspose.slides/textautofittype/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_CenterText](./get_centertext/)() | إذا كان [NullableBool::True](../../aspose.slides/nullablebool/) يجب أن يكون النص مركّزًا أفقيًا داخل الصندوق. قراءة [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | يعيد الهامش السفلي (نقاط) في [TextFrame](../../aspose.slides/textframe/). قد يؤدي تغيير هذه الخاصية إلى تأثير معين فقط على أجزاء المخطط التالية: [DataLabel](../datalabel/) و [DataLabelFormat](../datalabelformat/) (دعم كامل في PowerPoint 2013؛ في PowerPoint 2007 لا يوجد تأثير على العرض). قراءة **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | يعيد الهامش الأيسر (نقاط) في [TextFrame](../../aspose.slides/textframe/). قد يؤدي تغيير هذه الخاصية إلى تأثير معين فقط على أجزاء المخطط التالية: [DataLabel](../datalabel/) و [DataLabelFormat](../datalabelformat/) (دعم كامل في PowerPoint 2013؛ في PowerPoint 2007 لا يوجد تأثير على العرض). قراءة **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | يعيد الهامش الأيمن (نقاط) في [TextFrame](../../aspose.slides/textframe/). قد يؤدي تغيير هذه الخاصية إلى تأثير معين فقط على أجزاء المخطط التالية: [DataLabel](../datalabel/) و [DataLabelFormat](../datalabelformat/) (دعم كامل في PowerPoint 2013؛ في PowerPoint 2007 لا يوجد تأثير على العرض). قراءة **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | يعيد الهامش العلوي (نقاط) في [TextFrame](../../aspose.slides/textframe/). قد يؤدي تغيير هذه الخاصية إلى تأثير معين فقط على أجزاء المخطط التالية: [DataLabel](../datalabel/) و [DataLabelFormat](../datalabelformat/) (دعم كامل في PowerPoint 2013؛ في PowerPoint 2007 لا يوجد تأثير على العرض). قراءة **double**. |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | يحدد الدوران المخصص الذي يُطبق على النص داخل الصندوق المحدد. إذا لم يُحدد، يُستخدم دوران الشكل المرافق. إذا تم تحديده، يُطبق بشكل مستقل عن الشكل. أي أن الشكل يمكن أن يكون له دوران مضاف إلى دوران النص نفسه. القيمة الناتجة لدوران النص البصري المُجمّع من هذه الخاصية والنوع العمودي المحدد مسبقًا في الخاصية TextVerticalType. قراءة **float**. |
| virtual [Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | يحدد اتجاه النص. القيمة الناتجة لدوران النص البصري المُجمّع من هذه الخاصية والزاوية المخصصة في الخاصية RotationAngle. قراءة [Slides::TextVerticalType](../../aspose.slides/textverticaltype/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_WrapText](./get_wraptext/)() | صحيح إذا كان النص ملتفًا عند هوامش [TextFrame](../../aspose.slides/textframe/). قد يؤدي تغيير هذه الخاصية إلى تأثير معين فقط على أجزاء المخطط التالية: [DataLabel](../datalabel/) و [DataLabelFormat](../datalabelformat/) (دعم كامل في PowerPoint 2007/2013). قراءة [NullableBool](../../aspose.slides/nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكلة عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. تناظر عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يُهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | بناء نسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../../aspose.slides/textanchortype/)) | يضبط النص العمودي المثبت في [TextFrame](../../aspose.slides/textframe/). كتابة [TextAnchorType](../../aspose.slides/textanchortype/). |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../../aspose.slides/textautofittype/)) | يضبط وضع الملاءمة التلقائية للنص. قد يؤدي تغيير هذه الخاصية إلى تأثير معين فقط على أجزاء المخطط التالية: [DataLabel](../datalabel/) و [DataLabelFormat](../datalabelformat/) (دعم كامل في PowerPoint 2013؛ في PowerPoint 2007 لا يوجد تأثير على العرض). كتابة [TextAutofitType](../../aspose.slides/textautofittype/). |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../../aspose.slides/nullablebool/)) | إذا كان [NullableBool::True](../../aspose.slides/nullablebool/) يجب أن يكون النص مركّزًا أفقيًا داخل الصندوق. كتابة [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | يضبط الهامش السفلي (نقاط) في [TextFrame](../../aspose.slides/textframe/). قد يؤدي تغيير هذه الخاصية إلى تأثير معين فقط على أجزاء المخطط التالية: [DataLabel](../datalabel/) و [DataLabelFormat](../datalabelformat/) (دعم كامل في PowerPoint 2013؛ في PowerPoint 2007 لا يوجد تأثير على العرض). كتابة **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | يضبط الهامش الأيسر (نقاط) في [TextFrame](../../aspose.slides/textframe/). قد يؤدي تغيير هذه الخاصية إلى تأثير معين فقط على أجزاء المخطط التالية: [DataLabel](../datalabel/) و [DataLabelFormat](../datalabelformat/) (دعم كامل في PowerPoint 2013؛ في PowerPoint 2007 لا يوجد تأثير على العرض). كتابة **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | يضبط الهامش الأيمن (نقاط) في [TextFrame](../../aspose.slides/textframe/). قد يؤدي تغيير هذه الخاصية إلى تأثير معين فقط على أجزاء المخطط التالية: [DataLabel](../datalabel/) و [DataLabelFormat](../datalabelformat/) (دعم كامل في PowerPoint 2013؛ في PowerPoint 2007 لا يوجد تأثير على العرض). كتابة **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | يضبط الهامش العلوي (نقاط) في [TextFrame](../../aspose.slides/textframe/). قد يؤدي تغيير هذه الخاصية إلى تأثير معين فقط على أجزاء المخطط التالية: [DataLabel](../datalabel/) و [DataLabelFormat](../datalabelformat/) (دعم كامل في PowerPoint 2013؛ في PowerPoint 2007 لا يوجد تأثير على العرض). كتابة **double**. |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | يحدد الدوران المخصص الذي يُطبق على النص داخل الصندوق المحدد. إذا لم يُحدد، يُستخدم دوران الشكل المرافق. إذا تم تحديده، يُطبق بشكل مستقل عن الشكل. أي أن الشكل يمكن أن يكون له دوران مضاف إلى دوران النص نفسه. القيمة الناتجة لدوران النص البصري المُجمّع من هذه الخاصية والنوع العمودي المحدد مسبقًا في الخاصية TextVerticalType. كتابة **float**. |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/)) | يحدد اتجاه النص. القيمة الناتجة لدوران النص البصري المُجمّع من هذه الخاصية والزاوية المخصصة في الخاصية RotationAngle. كتابة [Slides::TextVerticalType](../../aspose.slides/textverticaltype/). |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../../aspose.slides/nullablebool/)) | صحيح إذا كان النص ملتفًا عند هوامش [TextFrame](../../aspose.slides/textframe/). قد يؤدي تغيير هذه الخاصية إلى تأثير معين فقط على أجزاء المخطط التالية: [DataLabel](../datalabel/) و [DataLabelFormat](../datalabelformat/) (دعم كامل في PowerPoint 2007/2013). كتابة [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط معامل القالب الـ n كإشارة ضعيفة (بدلاً من مشاركة). يسمح بتبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم بدلًا من ذلك المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم بدلًا من ذلك المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تناظر طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم بدلًا من ذلك المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم بدلًا من ذلك المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |
## انظر أيضًا

* فئة [Object](../../system/object/)
* مساحة الأسماء [Aspose::Slides::Charts](../)
* مكتبة [Aspose.Slides](../../)