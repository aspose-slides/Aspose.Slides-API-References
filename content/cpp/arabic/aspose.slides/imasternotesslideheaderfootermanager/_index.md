---
title: IMasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides للغة C++ مرجع API
description: يمثل مديرًا يحتفظ بسلوك تذييل شريحة ملاحظات رئيسية، وعناصر نائب التاريخ والوقت، ورقم الصفحة، وجميع العناصر النائبة الفرعية. العناصر النائبة الفرعية تعني أن العناصر النائبة موجودة على الشرائح المعتمدة على الملاحظات. تستخدم الشرائح المعتمدة على الملاحظات وتعتمد على شريحة ملاحظات رئيسية.
type: docs
weight: 2900
url: /ar/aspose.slides/imasternotesslideheaderfootermanager/
---
## IMasterNotesSlideHeaderFooterManager فئة

يمثل مديرًا يحتفظ بسلوك تذييل شريحة ملاحظات رئيسية، وعناصر نائب التاريخ والوقت، ورقم الصفحة، وجميع العناصر النائبة الفرعية. العناصر النائبة الفرعية تعني أن العناصر النائبة موجودة على الشرائح المعتمدة على الملاحظات. تستخدم الشرائح المعتمدة على الملاحظات وتعتمد على شريحة ملاحظات رئيسية.

```cpp
class IMasterNotesSlideHeaderFooterManager : public virtual Aspose::Slides::IBaseHandoutNotesSlideHeaderFooterManag
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة نقطية عائمة بأسلوب C# حيث تُconsidered NaN الاثنين متساويتين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليست مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة نقطية مزدوجة بأسلوب C# حيث تُconsidered NaN الاثنين متساويتين رغم أن IEC 60559:1989 يحدد أن NaN ليست مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual **bool** [get_IsDateTimeVisible](../ibaseslideheaderfootermanager/get_isdatetimevisible/)() | يجلب القيمة التي تشير إلى وجود عنصر نائب التاريخ والوقت. قراءة**bool**. |
| virtual **bool** [get_IsFooterVisible](../ibaseslideheaderfootermanager/get_isfootervisible/)() | يجلب القيمة التي تشير إلى وجود عنصر نائب التذييل. قراءة **bool**. |
| virtual **bool** [get_IsHeaderVisible](../ibasehandoutnotesslideheaderfootermanag/get_isheadervisible/)() | يجلب القيمة التي تشير إلى وجود عنصر نائب الرأس. قراءة **bool**. |
| virtual **bool** [get_IsSlideNumberVisible](../ibaseslideheaderfootermanager/get_isslidenumbervisible/)() | يجلب القيمة التي تشير إلى وجود عنصر نائب رقم الصفحة. قراءة**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يجلب بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يجلب النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل مثيلاً للنوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدع مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) | يضبط النص لعنصر نائب التاريخ والوقت في شريحة ملاحظات رئيسية وجميع العناصر النائبة للتاريخ والوقت الفرعية. العناصر النائبة الفرعية تعني أن العناصر النائبة موجودة على الشرائح المعتمدة على الملاحظات. تستخدم الشرائح المعتمدة على الملاحظات وتعتمد على شريحة ملاحظات رئيسية. |
| virtual void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) | يغيّر رؤية عنصر نائب التاريخ والوقت في شريحة ملاحظات رئيسية وجميع العناصر النائبة للتاريخ والوقت الفرعية. العناصر النائبة الفرعية تعني أن العناصر النائبة موجودة على الشرائح المعتمدة على الملاحظات. تستخدم الشرائح المعتمدة على الملاحظات وتعتمد على شريحة ملاحظات رئيسية. |
| virtual void [SetDateTimeText](../ibaseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) | يضبط النص لعنصر نائب التاريخ والوقت في الشريحة. |
| virtual void [SetDateTimeVisibility](../ibaseslideheaderfootermanager/setdatetimevisibility/)(**bool**) | يغيّر رؤية عنصر نائب التاريخ والوقت في الشريحة. |
| virtual void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) | يضبط النص لعنصر نائب التذييل في شريحة ملاحظات رئيسية وجميع العناصر النائبة للتذييل الفرعية. العناصر النائبة الفرعية تعني أن العناصر النائبة موجودة على الشرائح المعتمدة على الملاحظات. تستخدم الشرائح المعتمدة على الملاحظات وتعتمد على شريحة ملاحظات رئيسية. |
| virtual void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) | يغيّر رؤية عنصر نائب التذييل في شريحة ملاحظات رئيسية وجميع العناصر النائبة للتذييل الفرعية. العناصر النائبة الفرعية تعني أن العناصر النائبة موجودة على الشرائح المعتمدة على الملاحظات. تستخدم الشرائح المعتمدة على الملاحظات وتعتمد على شريحة ملاحظات رئيسية. |
| virtual void [SetFooterText](../ibaseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) | يضبط النص لعنصر نائب التذييل في الشريحة. |
| virtual void [SetFooterVisibility](../ibaseslideheaderfootermanager/setfootervisibility/)(**bool**) | يغيّر رؤية عنصر نائب التذييل في الشريحة. |
| virtual void [SetHeaderAndChildHeadersText](./setheaderandchildheaderstext/)([System::String](../../system/string/)) | يضبط النص لعنصر نائب الرأس في شريحة ملاحظات رئيسية وجميع العناصر النائبة للرأس الفرعية. العناصر النائبة الفرعية تعني أن العناصر النائبة موجودة على الشرائح المعتمدة على الملاحظات. تستخدم الشرائح المعتمدة على الملاحظات وتعتمد على شريحة ملاحظات رئيسية. |
| virtual void [SetHeaderAndChildHeadersVisibility](./setheaderandchildheadersvisibility/)(**bool**) | يغيّر رؤية عنصر نائب الرأس في شريحة ملاحظات رئيسية وجميع العناصر النائبة للرأس الفرعية. العناصر النائبة الفرعية تعني أن العناصر النائبة موجودة على الشرائح المعتمدة على الملاحظات. تستخدم الشرائح المعتمدة على الملاحظات وتعتمد على شريحة ملاحظات رئيسية. |
| virtual void [SetHeaderText](../ibasehandoutnotesslideheaderfootermanag/setheadertext/)([System::String](../../system/string/)) | يضبط النص لعنصر نائب الرأس في الشريحة. |
| virtual void [SetHeaderVisibility](../ibasehandoutnotesslideheaderfootermanag/setheadervisibility/)(**bool**) | يغيّر رؤية عنصر نائب الرأس في الشريحة. |
| virtual void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) | يغيّر رؤية عنصر نائب رقم الصفحة في شريحة ملاحظات رئيسية وجميع العناصر النائبة لرقم الصفحة الفرعية. العناصر النائبة الفرعية تعني أن العناصر النائبة موجودة على الشرائح المعتمدة على الملاحظات. تستخدم الشرائح المعتمدة على الملاحظات وتعتمد على شريحة ملاحظات رئيسية. |
| virtual void [SetSlideNumberVisibility](../ibaseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) | يغيّر رؤية عنصر نائب رقم الصفحة في الشريحة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n كإشارة ضعيفة (بدلاً من مشاركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يجلب القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ فك قفل عبارة C# lock(). استدع مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* فئة [IBaseHandoutNotesSlideHeaderFooterManag](../ibasehandoutnotesslideheaderfootermanag/)
* مساحة الاسم [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)