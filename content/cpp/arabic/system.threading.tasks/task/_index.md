---
title: Task
second_title: مرجع API Aspose.Slides للغة C++
description: يمثل عملية غير متزامنة يمكن انتظارها وتكوينها مع مهام أخرى.
type: docs
weight: 66
url: /ar/system.threading.tasks/task/
---
## فئة Task


يمثل عملية غير متزامنة يمكن انتظارها وتكوينها مع مهام أخرى.

```cpp
class Task : public System::IDisposable
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| void [Activate](./activate/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | يقوم بتنشيط المهمة للتنفيذ على المجدول. |
| void [AddCompletionAction](./addcompletionaction/)(const [Action](../../system/action/)<>\&) | يضيف فعل استمراري ليُنفذ عند الانتهاء. |
| void [Cancel](./cancel/)() | يُعلِّم المهمة كملغاة وينهي المهمة. |
| void [Complete](./complete/)() | يُعلِّم المهمة كمنجزة وينهي المهمة. |
| [Runtime::CompilerServices::ConfiguredTaskAwaitable](../../system.runtime.compilerservices/configuredtaskawaitable/) [ConfigureAwait](./configureawait/)(**bool**) const | يُعدّ كيفية سلوك الانتظار على هذه المهمة فيما يتعلق بالتقاط السياق. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[TaskPtr](../../system/taskptr/)\>\&) | ينشئ استمرارية تُنفّذ عند إكمال المهمة. |
| [RTaskPtr](../../system/rtaskptr/)\<TResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/), TResult\>\&) | ينشئ استمرارية تُنفّذ عند إكمال المهمة. |
| void [Deactivate](./deactivate/)() | يعطل المهمة من التنفيذ على المجدول الحالي إذا كان موجوداً. |
| void [Dispose](./dispose/)() override | يحرّر الموارد المرتبطة بالمهمة. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة الأعداد العائمة بأسلوب C# حيث تُعتبر NaN متساوية رغم أن IEC 60559:1989 تُصنف NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة الأعداد العائمة (double) بأسلوب C# حيث تُعتبر NaN متساوية رغم أن IEC 60559:1989 تُصنف NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| void [Execute](./execute/)() | ينفّذ دالة المهمة. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للأغراض الداخلية فقط. |
| const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& [get_AsyncState](./get_asyncstate/)() const | يحصل على كائن الحالة المعرّف من قبل المستخدم المرتبط بالمهمة. |
| static const [TaskPtr](../../system/taskptr/)\& [get_CompletedTask](./get_completedtask/)() | يحصل على مهمة مكتملة (فردية). |
| static [Nullable](../../system/nullable/)\<**int32_t**\> [get_CurrentId](./get_currentid/)() |  |
| [AggregateException](../../system/aggregateexception/) [get_Exception](./get_exception/)() const | يحصل على معرّف المهمة. |
| **int32_t** [get_Id](./get_id/)() const |  |
| **bool** [get_IsCanceled](./get_iscanceled/)() const | يحصل على ما إذا كانت المهمة قد انتهت بسبب الإلغاء. |
| **bool** [get_IsCompleted](./get_iscompleted/)() const | يحصل على ما إذا كانت المهمة قد اكتملت. |
| **bool** [get_IsFaulted](./get_isfaulted/)() const | يحصل على ما إذا كانت المهمة قد انتهت بسبب استثناء غير معالج. |
| const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\& [get_Scheduler](./get_scheduler/)() const | يحصل على المجدول المرتبط بهذه المهمة. |
| [TaskStatus](../taskstatus/) [get_Status](./get_status/)() const | يحصل على الحالة الحالية للمهمة. |
| [Runtime::CompilerServices::TaskAwaiter](../../system.runtime.compilerservices/taskawaiter/) [GetAwaiter](./getawaiter/)() const | يحصل على عنصر انتظار لهذه المهمة للاستخدام مع Await. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل بيانات عدّاد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثالا للنوع الموصوف بـ targetType. مماثل لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ عملية القفل في عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيّء جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعلاً، بل يهيّء كائنًا جديدًا ويسمح بنسخ الإنشاء للأنواع الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعلاً، بل يهيّء كائنًا جديدًا ويسمح بنسخ الإنشاء للأنواع الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| void [RunSynchronously](./runsynchronously/)() | يشغّل المهمة بشكل متزامن على الخيط الحالي. |
| void [RunSynchronously](./runsynchronously/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | يشغّل المهمة بشكل متزامن باستخدام المجدول المحدد. |
| void [set_Function](./set_function/)(const [FunctionT](./functiont/)\&) | يحدد الدالة الداخلية للتنفيذ. |
| void [set_Scheduler](./set_scheduler/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | يحدد المجدول المرتبط بهذه المهمة. |
| void [set_Status](./set_status/)([TaskStatus](../taskstatus/)) | يحدد حالة المهمة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط معامل القالب رقم n كإشارة ضعيفة (بدلاً من المشاركة). يتيح تحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعدّاد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [Start](./start/)() | يبدأ تنفيذ المهمة باستخدام المجدول الافتراضي. |
| void [Start](./start/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | يبدأ تنفيذ المهمة باستخدام المجدول المحدد. |
|  [Task](./task/)(const [Action](../../system/action/)<>\&) | يبني [Task](./) بفعل للتنفيذ. |
|  [Task](./task/)(const [Action](../../system/action/)<>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | يبني [Task](./) بفعل ورمز إلغاء. |
|  [Task](./task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | يبني [Task](./) بفعل حالة وكائن حالة. |
|  [Task](./task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | يبني [Task](./) بفعل حالة، حالة، ورمز إلغاء. |
|  [Task](./task/)() | منشئ داخلي لإنشاء مهام غير متهيئة. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ فك قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| void [Wait](./wait/)(const [CancellationToken](../../system.threading/cancellationtoken/)\&) | ينتظر اكتمال المهمة مع دعم الإلغاء. |
| void [Wait](./wait/)() | ينتظر اكتمال المهمة. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدّاد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |
|  [~Task](./~task/)() | المدمر. |

## التعريفات

| التعريف | الوصف |
| --- | --- |
| [FunctionT](./functiont/) | تنفيذ داخلي. غير مخصص لشفرة المستخدم. |

## ملاحظات

يوفر تنفيذًا بلغة C++ مشابهًا لـ [System.Threading.Tasks.Task](./) في .NET، يدعم الإلغاء، الاستمراريات، وأنماط async/await.

## انظر أيضًا

* فئة [IDisposable](../../system/idisposable/)
* مساحة الاسم [System::Threading::Tasks](../)
* مكتبة [Aspose.Slides](../../)