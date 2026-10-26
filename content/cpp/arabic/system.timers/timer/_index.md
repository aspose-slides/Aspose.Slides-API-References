---
title: Timer
second_title: مرجع API لـ Aspose.Slides للغة C++
description: المؤقت الذي يستدعي delegate في حلقة.
type: docs
weight: 14
url: /ar/system.timers/timer/
---
## فئة Timer


[Timer](./) التي تستدعي delegate في حلقة.

```cpp
class Timer : public System::ComponentModel::Component
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| void [Close](./close/)() | يوقف المؤقت، يحرر الموارد المخصصة. |
|  [Component](../../system.componentmodel/component/component/)() | معلومات RTTI. |
| void [Dispose](./dispose/)() | يوقف المؤقت، يحرر الموارد المخصصة. |
| void [Dispose](../../system.componentmodel/component/dispose/)(**bool**) | دعم نمط القابلية للتخلص؛ لا يفعل شيئًا. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنات النقطة العائمة بنمط C# حيث يُعتبر الـ NaNان متساويين حتى وإن كان وفق IEC 60559:1989 NaN غير مساوي لأي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنات النقطة العائمة بنمط C# حيث يُعتبر الـ NaNان متساويين حتى وإن كان وفق IEC 60559:1989 NaN غير مساوي لأي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| **bool** [get_AutoReset](./get_autoreset/)() const | يتحقق مما إذا كان المؤقت في وضع إعادة ضبط تلقائي. |
| **bool** [get_DesignMode](../../system.componentmodel/component/get_designmode/)() | يتحقق مما إذا كان المكوّن في وضع التصميم. |
| **bool** [get_Enabled](./get_enabled/)() const | يتحقق مما إذا كان المؤقت نشطًا. |
| **double** [get_Interval](./get_interval/)() const | يحصل على فترة المؤقت. |
| **bool** [get_IsStopped](./get_isstopped/)() const | يتحقق مما إذا كان المؤقت متوقفًا. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | تنفيذ تأمين العبارة C# lock(). استدعِها مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيء جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا حقًا، فقط يهيء كائنًا جديدًا ويسمح بنسخ بناء الفروع. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | مُعامل الإسناد. لا ينسخ شيئًا حقًا، فقط يهيء كائنًا جديدًا ويسمح بنسخ بناء الفروع. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_AutoReset](./set_autoreset/)(**bool**) | يضبط المؤقت في وضع إعادة ضبط تلقائي أو يخرجه منه. |
| void [set_Enabled](./set_enabled/)(**bool**) | يبدأ أو يوقف المؤقت. بدء المؤقت لا يعيد عدّ الوقت إذا كان المؤقت قيد التنفيذ بالفعل. |
| void [set_Interval](./set_interval/)(**double**) | يضبط فترة المؤقت. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يعيّن الوسيط القالبي الـ n كمؤشر ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [Start](./start/)() | يبدأ المؤقت. لا يعيد عدّ الوقت إذا كان المؤقت قيد التنفيذ بالفعل. |
| void [Stop](./stop/)() | يوقف المؤقت. |
|  [Timer](./timer/)() | معلومات RTTI. |
|  [Timer](./timer/)(**double**) | ينشئ مؤقتًا متوقفًا بالفترة المحددة. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | تنفيذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | تنفيذ إلغاء تأمين العبارة C# lock(). استدعِها مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |
## انظر أيضًا

* الفئة [Component](../../system.componentmodel/component/)
* النطاق [System::Timers](../)
* المكتبة [Aspose.Slides](../../)