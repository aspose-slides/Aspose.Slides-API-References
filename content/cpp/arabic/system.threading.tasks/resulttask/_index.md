---
title: ResultTask
second_title: مرجع API لـ Aspose.Slides للغة C++
description: تخصص مهمة يعيد قيمة النتيجة عند الانتهاء.
type: docs
weight: 40
url: /ar/system.threading.tasks/resulttask/
---
## ResultTask فئة

A [Task](../task/) specialization that returns a result value upon completion.

```cpp
template<typename T>class ResultTask : public System::Threading::Tasks::Task
```

### معلمات القالب

| معامل | وصف |
| --- | --- |
| T | The type of the result value returned by the task |
## الطرق

| طريقة | وصف |
| --- | --- |
| void [Activate](../task/activate/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | يفعل المهمة للتنفيذ على مجدول. |
| void [AddCompletionAction](../task/addcompletionaction/)(const [Action](../../system/action/)<>\&) | يضيف إجراءً استكمالًا يتم تنفيذه عند الانتهاء. |
| void [Cancel](../task/cancel/)() | يحدد المهمة كملغاة وينهي المهمة. |
| void [Complete](./complete/)(const T\&) | يضبط قيمة النتيجة للمهمة ويكملها. |
| void [Complete](../task/complete/)() | يحدد المهمة كمنجزة وينهي المهمة. |
| [Runtime::CompilerServices::ConfiguredResultTaskAwaitable](../../system.runtime.compilerservices/configuredresulttaskawaitable/)\<T\> [ConfigureAwait](./configureawait/)(**bool**) const | يضبط كيفية تصرف الانتظار على هذه المهمة الناتجة فيما يتعلق بالتقاط السياق. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[RTaskPtr](../../system/rtaskptr/)\<T\>\>\&) | ينشئ استكمالًا يتم تنفيذها عندما تكتمل المهمة الناتجة. |
| [RTaskPtr](../../system/rtaskptr/)\<TNewResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[RTaskPtr](../../system/rtaskptr/)\<T\>, TNewResult\>\&) | ينشئ استكمالًا يتم تنفيذها عندما تكتمل المهمة الناتجة. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[TaskPtr](../../system/taskptr/)\>\&) | ينشئ استكمالًا يتم تنفيذها عندما تكتمل المهمة. |
| [RTaskPtr](../../system/rtaskptr/)\<TResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/), TResult\>\&) | ينشئ استكمالًا يتم تنفيذها عندما تكتمل المهمة. |
| void [Deactivate](../task/deactivate/)() | يعطل المهمة للتنفيذ على المجدول الحالي إذا كان موجودًا. |
| void [Dispose](../task/dispose/)() override | يطلق الموارد المرتبطة بالمهمة. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يوزع مقارنة النقطة العائمة بأسلوب C# حيث يُعتَبر NaNانين متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يوزع مقارنة النقطة العائمة بأسلوب C# حيث يُعتَبر NaNانين متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| void [Execute](../task/execute/)() | ينفّذ دالة المهمة. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& [get_AsyncState](../task/get_asyncstate/)() const | يحصل على كائن الحالة المعرّف من قبل المستخدم المرتبط بالمهمة. |
| static const [TaskPtr](../../system/taskptr/)\& [get_CompletedTask](../task/get_completedtask/)() | يحصل على مهمة مكتملة (نقطة منفردة) |
| static [Nullable](../../system/nullable/)\<**int32_t**\> [get_CurrentId](../task/get_currentid/)() |  |
| [AggregateException](../../system/aggregateexception/) [get_Exception](../task/get_exception/)() const | يحصل على المعرف الخاص بالمهمة. |
| **int32_t** [get_Id](../task/get_id/)() const |  |
| **bool** [get_IsCanceled](../task/get_iscanceled/)() const | يحصل على ما إذا كانت المهمة قد انتهت بسبب الإلغاء. |
| **bool** [get_IsCompleted](../task/get_iscompleted/)() const | يحصل على ما إذا كانت المهمة قد اكتملت. |
| **bool** [get_IsFaulted](../task/get_isfaulted/)() const | يحصل على ما إذا كانت المهمة قد انتهت بسبب استثناء غير معالج. |
| T [get_Result](./get_result/)() | يحصل على نتيجة العملية غير المتزامنة. |
| const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\& [get_Scheduler](../task/get_scheduler/)() const | يحصل على المجدول المرتبط بهذه المهمة. |
| [TaskStatus](../taskstatus/) [get_Status](../task/get_status/)() const | يحصل على الحالة الحالية للمهمة. |
| [Runtime::CompilerServices::ResultTaskAwaiter](../../system.runtime.compilerservices/resulttaskawaiter/)\<T\> [GetAwaiter](./getawaiter/)() const | يحصل على مُنتظر لهذه المهمة الناتجة للاستخدام مع Await. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عدّاد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مكافئ طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مكافئ لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموضّح بـ targetType. مكافئ لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل بيان C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مكافئ طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات حسب المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات حسب المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع null. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
|  [ResultTask](./resulttask/)(const [Func](../../system/func/)\<T\>\&) | ينشئ [ResultTask](./) مع دالة تُرجع قيمة. |
|  [ResultTask](./resulttask/)() | تنفيذ داخلي. غير مخصص لشفرة المستخدم. |
|  [ResultTask](./resulttask/)(const T\&) | منشئ داخلي لإنشاء مهام نتيجة مع النتيجة المحددة. |
| void [RunSynchronously](../task/runsynchronously/)() | يشغّل المهمة بشكل متزامن على الخيط الحالي. |
| void [RunSynchronously](../task/runsynchronously/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | يشغّل المهمة بشكل متزامن باستخدام المجدول المحدد. |
| void [set_Function](../task/set_function/)(const [FunctionT](../task/functiont/)\&) | يضبط الدالة الداخلية للتنفيذ. |
| void [set_Result](./set_result/)(const T\&) | يضبط قيمة النتيجة للمهمة. |
| void [set_Scheduler](../task/set_scheduler/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | يضبط المجدول المرتبط بهذه المهمة. |
| void [set_Status](../task/set_status/)([TaskStatus](../taskstatus/)) | يضبط حالة المهمة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط المتغيّر القالبي الـ n'th كإشارة ضعيفة (بدلاً من مشتركة). يتيح تبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عدّاد المرجع المشترك ويعيد قيمته. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [Start](../task/start/)() | يبدأ تنفيذ المهمة باستخدام المجدول الافتراضي. |
| void [Start](../task/start/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | يبدأ تنفيذ المهمة باستخدام المجدول المحدد. |
|  [Task](../task/task/)(const [Action](../../system/action/)<>\&) | ينشئ [Task](../task/) مع إجراء للتنفيذ. |
|  [Task](../task/task/)(const [Action](../../system/action/)<>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | ينشئ [Task](../task/) مع إجراء ورمز إلغاء. |
|  [Task](../task/task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | ينشئ [Task](../task/) مع إجراء يحتفل بالحالة وكائن حالة. |
|  [Task](../task/task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | ينشئ [Task](../task/) مع إجراء يحتفل بالحالة، حالة، ورمز إلغاء. |
|  [Task](../task/task/)() | منشئ داخلي لإنشاء مهام غير مهيأة. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مكافئ طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ فك قفل بيان C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| void [Wait](../task/wait/)(const [CancellationToken](../../system.threading/cancellationtoken/)\&) | ينتظر حتى تكتمل المهمة مع دعم الإلغاء. |
| void [Wait](../task/wait/)() | ينتظر حتى تكتمل المهمة. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |
|  [~Task](../task/~task/)() | المدمر. |
## ملاحظات

يمثل عملية غير متزامنة تنتج نتيجة، مشابهة لـ System.Threading.Tasks.Task<TResult> في .NET 
## انظر أيضاً

* الفئة [Task](../task/)
* النطاق [System::Threading::Tasks](../)
* المكتبة [Aspose.Slides](../../)