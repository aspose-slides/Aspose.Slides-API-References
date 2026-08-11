---
title: MasterHandoutSlideHeaderFooterManager
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يمثل المدير الذي يتحكم في سلوك عناصر نائب شرائح النسخة المطبوعّة الرئيسية، بما في ذلك عنصر نائب الترويسة.
type: docs
weight: 4421
url: /ar/aspose.slides/masterhandoutslideheaderfootermanager/
---
## MasterHandoutSlideHeaderFooterManager الفئة


Represents manager which holds behavior of the master handout slide placeholders, including header placeholder.

```cpp
class MasterHandoutSlideHeaderFooterManager : public Aspose::Slides::BaseHandoutNotesSlideHeaderFooterManager,
                                              public Aspose::Slides::IMasterHandoutSlideHeaderFooterManager
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة نقطية عائمة بأسلوب C# حيث تُعتبر NaN-انّان متساويتين على الرغم من أن معيار IEC 60559:1989 يذكر أن NaN ليست مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة نقطية عائمة بأسلوب C# حيث تُعتبر NaN-انّان متساويتين على الرغم من أن معيار IEC 60559:1989 يذكر أن NaN ليست مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| **bool** [get_IsDateTimeVisible](../baseslideheaderfootermanager/get_isdatetimevisible/)() override | يحصل على قيمة تشير إلى وجود عنصر نائب لتاريخ-وقت. قراءة**bool**. |
| **bool** [get_IsFooterVisible](../baseslideheaderfootermanager/get_isfootervisible/)() override | يحصل على قيمة تشير إلى وجود عنصر نائب للتذييل. قراءة **bool**. |
| **bool** [get_IsHeaderVisible](../basehandoutnotesslideheaderfootermanager/get_isheadervisible/)() override | يحصل على قيمة تشير إلى وجود عنصر نائب للترويسة. قراءة **bool**. |
| **bool** [get_IsSlideNumberVisible](../baseslideheaderfootermanager/get_isslidenumbervisible/)() override | يحصل على قيمة تشير إلى وجود عنصر نائب لرقم الصفحة. قراءة**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر لأسلوب C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح التجزئة للكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. تناظر لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل جملة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر لأسلوب C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [SetDateTimeText](../baseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) override | يضبط النص لعنصر نائب تاريخ-وقت في الشريحة. |
| void [SetDateTimeVisibility](../baseslideheaderfootermanager/setdatetimevisibility/)(**bool**) override | يغيّر رؤية عنصر نائب تاريخ-وقت في الشريحة. |
| void [SetFooterText](../baseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) override | يضبط النص لعنصر نائب التذييل في الشريحة. |
| void [SetFooterVisibility](../baseslideheaderfootermanager/setfootervisibility/)(**bool**) override | يغيّر رؤية عنصر نائب التذييل في الشريحة. |
| void [SetHeaderText](../basehandoutnotesslideheaderfootermanager/setheadertext/)([System::String](../../system/string/)) override | يضبط النص لعنصر نائب الترويسة في الشريحة. |
| void [SetHeaderVisibility](../basehandoutnotesslideheaderfootermanager/setheadervisibility/)(**bool**) override | يغيّر رؤية عنصر نائب الترويسة في الشريحة. |
| void [SetSlideNumberVisibility](../baseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) override | يغيّر رؤية عنصر نائب رقم الصفحة في الشريحة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النوني للقالب كإشارة ضعيفة (بدلاً من المشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تناظر لأسلوب C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل جملة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [BaseHandoutNotesSlideHeaderFooterManager](../basehandoutnotesslideheaderfootermanager/)
* الفئة [IMasterHandoutSlideHeaderFooterManager](../imasterhandoutslideheaderfootermanager/)
* النطاق [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)