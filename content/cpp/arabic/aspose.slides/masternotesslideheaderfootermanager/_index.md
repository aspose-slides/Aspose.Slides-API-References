---
title: MasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides لـ C++ مرجع API
description: يمثل مديرًا يتحكم بسلوك تذييل شريحة الملاحظات الرئيسية، وعناصر النائب للوقت والتاريخ، ورقم الصفحة، وجميع عناصر النائب الفرعية. تعني عناصر النائب الفرعية أن العناصر النائبة موجودة على شرائح الملاحظات المعتمدة. تستخدم شرائح الملاحظات المعتمدة وتعتمد على شريحة الملاحظات الرئيسية.
type: docs
weight: 4460
url: /ar/aspose.slides/masternotesslideheaderfootermanager/
---
## MasterNotesSlideHeaderFooterManager فئة

يمثل المدير الذي يتحكم في سلوك تذييل شريحة الملاحظات الرئيسة، وعناصر النائب للوقت والتاريخ، ورقم الصفحة وجميع عناصر النائب الفرعية. تعني عناصر النائب الفرعية أن عناصر النائب موجودة على شرائح الملاحظات المعتمدة. تستخدم شرائح الملاحظات المعتمدة وتعتمد على شريحة الملاحظات الرئيسة.

```cpp
class MasterNotesSlideHeaderFooterManager : public Aspose::Slides::BaseHandoutNotesSlideHeaderFooterManager,
                                            public Aspose::Slides::IMasterNotesSlideHeaderFooterManager
```

## طرق

| طريقة | وصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يتم اعتبار NaNين متساويين على الرغم من أنه وفقًا لمعيار IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يتم اعتبار NaNين متساويين على الرغم من أنه وفقًا لمعيار IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| **bool** [get_IsDateTimeVisible](../baseslideheaderfootermanager/get_isdatetimevisible/)() override | يحصل على قيمة تشير إلى وجود عنصر نائب للوقت والتاريخ. قراءة **bool**. |
| **bool** [get_IsFooterVisible](../baseslideheaderfootermanager/get_isfootervisible/)() override | يحصل على قيمة تشير إلى وجود عنصر نائب للتذييل. قراءة **bool**. |
| **bool** [get_IsHeaderVisible](../basehandoutnotesslideheaderfootermanager/get_isheadervisible/)() override | يحصل على قيمة تشير إلى وجود عنصر نائب للرأس. قراءة **bool**. |
| **bool** [get_IsSlideNumberVisible](../baseslideheaderfootermanager/get_isslidenumbervisible/)() override | يحصل على قيمة تشير إلى وجود عنصر نائب لرقم الصفحة. قراءة **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. مماثل لمشغل 'is' في C#. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). يُستدعى مباشرةً أو يستخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) override | يضبط النص لعنصر نائب للوقت والتاريخ في الشريحة الرئيسة وجميع عناصر النائب للوقت والتاريخ الفرعية. تعني عناصر النائب الفرعية أن عناصر النائب موجودة على شرائح الملاحظات المعتمدة. تستخدم شرائح الملاحظات المعتمدة وتعتمد على شريحة الملاحظات الرئيسة. |
| void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) override | يغيّر رؤية عنصر نائب الوقت والتاريخ في الشريحة الرئيسة وجميع عناصر النائب للوقت والتاريخ الفرعية. تعني عناصر النائب الفرعية أن عناصر النائب موجودة على شرائح الملاحظات المعتمدة. تستخدم شرائح الملاحظات المعتمدة وتعتمد على شريحة الملاحظات الرئيسة. |
| void [SetDateTimeText](../baseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) override | يضبط النص لعنصر نائب الوقت والتاريخ في الشريحة. |
| void [SetDateTimeVisibility](../baseslideheaderfootermanager/setdatetimevisibility/)(**bool**) override | يغيّر رؤية عنصر نائب الوقت والتاريخ في الشريحة. |
| void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) override | يضبط النص لعنصر نائب التذييل في الشريحة الرئيسة وجميع عناصر النائب للتذييل الفرعية. تعني عناصر النائب الفرعية أن عناصر النائب موجودة على شرائح الملاحظات المعتمدة. تستخدم شرائح الملاحظات المعتمدة وتعتمد على شريحة الملاحظات الرئيسة. |
| void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) override | يغيّر رؤية عنصر نائب التذييل في الشريحة الرئيسة وجميع عناصر النائب للتذييل الفرعية. تعني عناصر النائب الفرعية أن عناصر النائب موجودة على شرائح الملاحظات المعتمدة. تستخدم شرائح الملاحظات المعتمدة وتعتمد على شريحة الملاحظات الرئيسة. |
| void [SetFooterText](../baseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) override | يضبط النص لعنصر نائب التذييل في الشريحة. |
| void [SetFooterVisibility](../baseslideheaderfootermanager/setfootervisibility/)(**bool**) override | يغيّر رؤية عنصر نائب التذييل في الشريحة. |
| void [SetHeaderAndChildHeadersText](./setheaderandchildheaderstext/)([System::String](../../system/string/)) override | يضبط النص لعنصر نائب الرأس في شريحة الملاحظات الرئيسة وجميع عناصر النائب للرأس الفرعية. تعني عناصر النائب الفرعية أن عناصر النائب موجودة على شرائح الملاحظات المعتمدة. تستخدم شرائح الملاحظات المعتمدة وتعتمد على شريحة الملاحظات الرئيسة. |
| void [SetHeaderAndChildHeadersVisibility](./setheaderandchildheadersvisibility/)(**bool**) override | يغيّر رؤية عنصر نائب الرأس في شريحة الملاحظات الرئيسة وجميع عناصر النائب للرأس الفرعية. تعني عناصر النائب الفرعية أن عناصر النائب موجودة على شرائح الملاحظات المعتمدة. تستخدم شرائح الملاحظات المعتمدة وتعتمد على شريحة الملاحظات الرئيسة. |
| void [SetHeaderText](../basehandoutnotesslideheaderfootermanager/setheadertext/)([System::String](../../system/string/)) override | يضبط النص لعنصر نائب الرأس في الشريحة. |
| void [SetHeaderVisibility](../basehandoutnotesslideheaderfootermanager/setheadervisibility/)(**bool**) override | يغيّر رؤية عنصر نائب الرأس في الشريحة. |
| void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) override | يغيّر رؤية عنصر نائب رقم الصفحة في الشريحة الرئيسة وجميع عناصر النائب لرقم الصفحة الفرعية. تعني عناصر النائب الفرعية أن عناصر النائب موجودة على شرائح الملاحظات المعتمدة. تستخدم شرائح الملاحظات المعتمدة وتعتمد على شريحة الملاحظات الرئيسة. |
| void [SetSlideNumberVisibility](../baseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) override | يغيّر رؤية عنصر نائب رقم الصفحة في الشريحة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n ليكون مؤشرًا ضعيفًا (بدلاً من المشترك). يسمح بتبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويُعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك قفل عبارة C# lock(). يُستدعى مباشرةً أو يستخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يبدى الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* فئة [BaseHandoutNotesSlideHeaderFooterManager](../basehandoutnotesslideheaderfootermanager/)
* فئة [IMasterNotesSlideHeaderFooterManager](../imasternotesslideheaderfootermanager/)
* نطاق [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)