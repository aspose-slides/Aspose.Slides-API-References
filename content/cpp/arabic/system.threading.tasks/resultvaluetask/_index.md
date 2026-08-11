---
title: ResultValueTask
second_title: مرجع Aspose.Slides للغة C++
description: يمثل نوعًا شبيهًا بالمهمة هجينًا يمكنه تغليف إما قيمة نتيجة مباشرة أو ResultTask<T>.
type: docs
weight: 53
url: /ar/system.threading.tasks/resultvaluetask/
---
## ResultValueTask فئة

Represents a hybrid task-like type that can wrap either a direct result value or a ResultTask<T>.

```cpp
template<typename T>class ResultValueTask : public System::IEquatable<ResultValueTask<T>>,
                                            public System::Details::BoxableObjectBase
```

### معاملات القالب

| Parameter | الوصف |
| --- | --- |
| T | نوع النتيجة التي ينتجها المهمة. |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [RTaskPtr](../../system/rtaskptr/)\<T\> [AsTask](./astask/)() const | يحول هذا [ResultValueTask](./) إلى مؤشر مشترك إلى ResultTask<T>. |
| [Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable](../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)\<T\> [ConfigureAwait](./configureawait/)(**bool**) const | يضبط مُنتظرًا لهذه المهمة. |
| **bool** [Equals](./equals/)([ResultValueTask](./)) override | يحدد ما إذا كان هذا الكائن يساوي كائن [ResultValueTask](./) آخر. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | يحدد ما إذا كان هذا الكائن يساوي كائنًا آخر. |
| virtual **bool** [Equals](../../system/iequatable/equals/)(T) | يحدد ما إذا كانت الكائنات الحالية والمحددة متساوية. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين رغم أنه وفقًا لمعيار IEC 60559:1989 فإن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين رغم أنه وفقًا لمعيار IEC 60559:1989 فإن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| **bool** [get_IsCanceled](./get_iscanceled/)() const | يحصل على قيمة تشير إلى ما إذا كانت المهمة قد انتهت بسبب الإلغاء. |
| **bool** [get_IsCompleted](./get_iscompleted/)() const | يحصل على قيمة تشير إلى ما إذا كانت المهمة قد انتهت. |
| **bool** [get_IsCompletedSuccessfully](./get_iscompletedsuccessfully/)() const | يحصل على قيمة تشير إلى ما إذا كانت المهمة قد انتهت بنجاح. |
| **bool** [get_IsFaulted](./get_isfaulted/)() const | يحصل على قيمة تشير إلى ما إذا كانت المهمة قد انتهت بسبب استثناء غير معالج. |
| T [get_Result](./get_result/)() | يحصل على نتيجة المهمة المكتملة. |
| [Runtime::CompilerServices::ResultValueTaskAwaiter](../../system.runtime.compilerservices/resultvaluetaskawaiter/)\<T\> [GetAwaiter](./getawaiter/)() const | يحصل على مُنتظر لهذا المهمة لدعم تعبيرات الانتظار. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجعية المرتبطة بهذا الكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير نداء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل عينة من النوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويمكّن إنشاء نسخ من الفئات الفرعية. |
| **bool** [operator!=](./operator_not_equal/)(const [ResultValueTask](./)\&) const | عامل عدم المساواة لـ [ResultValueTask](./). |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويمكّن إنشاء نسخ من الفئات الفرعية. |
| **bool** [operator==](./operator_equal_equal/)(const [ResultValueTask](./)\&) const | عامل المساواة لـ [ResultValueTask](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن قيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجعية المشتركة بالقيمة المحددة. |
|  [ResultValueTask](./resultvaluetask/)() | يبني [ResultValueTask](./) فارغًا غير مهيأ. |
|  [ResultValueTask](./resultvaluetask/)(const T\&) | يبني [ResultValueTask](./) مكتملًا بالنتيجة المحددة. |
|  [ResultValueTask](./resultvaluetask/)(const [RTaskPtr](../../system/rtaskptr/)\<T\>\&) | يبني [ResultValueTask](./) من مؤشر مشترك إلى ResultTask<T>. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضع الوسيط القالب رقم n كمؤشر ضعيف (بدلاً من مشترك). يسمح بتبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجعية المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجعية المشتركة. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجعية المشتركة. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجعية الضعيفة. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجعية الضعيفة. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## ملاحظات

[ResultValueTask](./) يجمع بين فوائد [ValueTask](../valuetask/) (تقليل التخصيصات للنتائج المتزامنة) مع القدرة على تغليف كائنات ResultTask<T> الموجودة. يوفر واجهة قابلة للانتظار ومجموعة من طرق فحص حالة المهمة.

## انظر أيضًا

* الفئة [IEquatable](../../system/iequatable/)
* فضاء الأسماء [System::Threading::Tasks](../)
* المكتبة [Aspose.Slides](../../)