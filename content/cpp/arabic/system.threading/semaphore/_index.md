---
title: Semaphore
second_title: مرجع API Aspose.Slides للـ C++
description: "تنفيذ Semaphore. يجب تخصيص كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم أبدًا بإنشاء مثال من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيتسبب ذلك في أخطاء زمن التشغيل و/أو أخطاء التأكيد. دائمًا قم بلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 183
url: /ar/system.threading/semaphore/
---
## Semaphore الفئة

[Semaphore](./) التنفيذ. يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم أبدًا بإنشاء مثال من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيتسبب ذلك في أخطاء زمن التشغيل و/أو أخطاء التأكيد. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيلة إدخال.

```cpp
class Semaphore : public System::Threading::WaitHandle
```

## الطرق

| Method | Description |
| --- | --- |
| virtual void [Close](../waithandle/close/)() | يطلق أي مورد مرتبط بالمقبض. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام تعابير C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaN قيمتين متساويتين رغم أن IEC 60559:1989 تنص على أن NaN ليست مساوية لأي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaN قيمتين متساويتين رغم أن IEC 60559:1989 تنص على أن NaN ليست مساوية لأي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [wait_handle_t](../wait_handle_t/) [get_Handle](../waithandle/get_handle/)() | يحصل على المقبض. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لدالة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثالًا لنوع موضح بواسطة targetType. مماثل لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لدالة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيء جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، بل يهيء كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | معامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيء كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص خاص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) في حالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص خاص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) في حالة السلاسل. |
| int [Release](./release/)() | يطلق القفل على semaphore. |
| int [Release](./release/)(int) | يطلق عدة أقفال على semaphore. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual **bool** [Reset](./reset/)() | يضبط semaphore إلى حالة غير مُشارة. غير مدعوم. |
|  [Semaphore](./semaphore/)(int, int) | ينشئ semaphore غير مسمى. |
|  [Semaphore](./semaphore/)(int, int, const [String](../../system/string/)\&) | ينشئ semaphore مسمى. |
|  [Semaphore](./semaphore/)(int, int, const [String](../../system/string/)\&, **bool**\&) | ينشئ semaphore مسمى. |
| virtual **bool** [Set](./set/)() | يضبط semaphore إلى حالة مُشارة. غير مدعوم. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضع الوسيط القالب nth ك مؤشر ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويُعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لدالة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| static **bool** [WaitAll](../waithandle/waitall/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[WaitHandle](../waithandle/)\>\>\&, int) | ينتظر جميع المقابض لتطلق. |
| static **bool** [WaitAll](../waithandle/waitall/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[WaitHandle](../waithandle/)\>\>\&, [TimeSpan](../../system/timespan/)) | ينتظر جميع المقابض لتطلق. |
| static **bool** [WaitAll](../waithandle/waitall/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[WaitHandle](../waithandle/)\>\>\&) | ينتظر جميع المقابض لتطلق. |
| static int [WaitAny](../waithandle/waitany/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[WaitHandle](../waithandle/)\>\>\&, int) | ينتظر أي من المقابض لتطلق. |
| static int [WaitAny](../waithandle/waitany/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[WaitHandle](../waithandle/)\>\>\&, [TimeSpan](../../system/timespan/)) | ينتظر أي من المقابض لتطلق. |
| static int [WaitAny](../waithandle/waitany/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[WaitHandle](../waithandle/)\>\>\&) | ينتظر أي من المقابض لتطلق. |
| **bool** [WaitOne](./waitone/)() override | يقفل semaphore. ينفذ انتظارًا غير محدود إذا لزم الأمر. |
| **bool** [WaitOne](./waitone/)(int) override | يقفل semaphore. ينفذ الانتظار إذا لزم الأمر. |
| virtual **bool** [WaitOne](../waithandle/waitone/)([TimeSpan](../../system/timespan/)) | ينتظر للمقبض ليطلق. |
| virtual **bool** [WaitOne](../waithandle/waitone/)(int, **bool**) | ينتظر للمقبض ليطلق. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |
| virtual  [~WaitHandle](../waithandle/~waithandle/)() | المُهدم. |

## الحقول

| Field | Description |
| --- | --- |
| static [WaitTimeout](../waithandle/waittimeout/) | قيمة خاصة ليتم إرجاعها من الدالة وإلا إرجاع فهرس الكائن المُشار إليه في المصفوفة، إذا تجاوزت المهلة ولم يُصدر شيء. |

## انظر أيضًا

* الفئة [WaitHandle](../waithandle/)
* النطاق [System::Threading](../)
* المكتبة [Aspose.Slides](../../)