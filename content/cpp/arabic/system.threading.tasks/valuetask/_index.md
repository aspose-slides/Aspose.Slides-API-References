---
title: ValueTask
second_title: Aspose.Slides لـ C++ مرجع API
description: يوفر نتيجة يمكن انتظارها لعملية غير متزامنة.
type: docs
weight: 92
url: /ar/system.threading.tasks/valuetask/
---
## فئة ValueTask

Provides an awaitable result of an asynchronous operation.

```cpp
class ValueTask : public System::IEquatable<ValueTask>,
                  public System::Details::BoxableObjectBase
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [TaskPtr](../../system/taskptr/) [AsTask](./astask/)() const | يحوِّل هذا [ValueTask](./) إلى مؤشر مشترك إلى [Task](../task/). |
| [Runtime::CompilerServices::ConfiguredValueTaskAwaitable](../../system.runtime.compilerservices/configuredvaluetaskawaitable/) [ConfigureAwait](./configureawait/)(**bool**) const | يُعدّ مُنتظرًا لهذه المهمة. |
| **bool** [Equals](./equals/)([ValueTask](./)) override | يحدد ما إذا كانت هذه العينة مساوية لعينة [ValueTask](./) أخرى. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | يحدد ما إذا كانت هذه العينة مساوية لكائن آخر. |
| virtual **bool** [Equals](../../system/iequatable/equals/)(T) | يحدد ما إذا كان الكائنان الحالي والمحدد متساويين. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يُعتبر NaNانان متساويين حتى وإن كان وفقًا لـ IEC 60559:1989 لا يُعتبر NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يُعتبر NaNانان متساويين حتى وإن كان وفقًا لـ IEC 60559:1989 لا يُعتبر NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| **bool** [get_IsCanceled](./get_iscanceled/)() const | يحصل على قيمة تشير إلى ما إذا كانت المهمة انتهت بسبب الإلغاء. |
| **bool** [get_IsCompleted](./get_iscompleted/)() const | يحصل على قيمة تشير إلى ما إذا كانت المهمة قد انتهت. |
| **bool** [get_IsCompletedSuccessfully](./get_iscompletedsuccessfully/)() const | يحصل على قيمة تشير إلى ما إذا كانت المهمة انتهت بنجاح. |
| **bool** [get_IsFaulted](./get_isfaulted/)() const | يحصل على قيمة تشير إلى ما إذا كانت المهمة انتهت بسبب استثناء غير معالج. |
| [Runtime::CompilerServices::ValueTaskAwaiter](../../system.runtime.compilerservices/valuetaskawaiter/) [GetAwaiter](./getawaiter/)() const | يحصل على مُنتظر لهذه المهمة لدعم تعابير await. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عدّاد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تمثيل الكائنات المخصَّصة عبر التجزئة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل عينة من النوع الموصوف بواسطة targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصَّصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعلًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| **bool** [operator!=](./operator_not_equal/)(const [ValueTask](./)\&) const | عامل عدم المساواة لـ [ValueTask](./). |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعلًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| **bool** [operator==](./operator_equal_equal/)(const [ValueTask](./)\&) const | عامل المساواة لـ [ValueTask](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي الـ n إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتبديل المؤشرات في الحاويات إلى وضعية الضعيفة. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصَّصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
|  [ValueTask](./valuetask/)() | ينشئ [ValueTask](./) فارغًا غير مهيأ. |
|  [ValueTask](./valuetask/)(const [TaskPtr](../../system/taskptr/)\&) | ينشئ [ValueTask](./) من مؤشر مشترك إلى [Task](../task/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر كل بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [IEquatable](../../system/iequatable/)
* مساحة الاسم [System::Threading::Tasks](../)
* المكتبة [Aspose.Slides](../../)