---
title: "System::Threading::Tasks"
second_title: مرجع API لـ Aspose.Slides للغة C++
description: 
type: docs
weight: 1015
url: /ar/system.threading.tasks/
---
## الفئات

| الفئة | الوصف |
| --- | --- |
| [Parallel](./parallel/) | يوفر دعمًا للحلقات المتوازية والمناطق. |
| [ParallelLoopResult](./parallelloopresult/) | يوفر حالة إكمال حلقة [Parallel](./parallel/). |
| [ParallelOptions](./paralleloptions/) | يخزن الخيارات التي تُكوّن تشغيل الأساليب على الفئة [Parallel](./parallel/). |
| [ResultTask](./resulttask/) | تخصص [Task](./task/) يُعيد قيمة ناتج عند الانتهاء. |
| [ResultValueTask](./resultvaluetask/) | يمثل نوعًا شبيهًا بالمهمة هجينيًا يمكنه احتواء إما قيمة ناتج مباشرة أو ResultTask<T>. |
| [Task](./task/) | يمثل عملية غير متزامنة يمكن انتظارها وتكوينها مع مهام أخرى. |
| [TaskScheduler](./taskscheduler/) | يمثل كائنًا يتعامل مع العمل منخفض المستوى لقائمة المهام على الخيوط. |
| [ValueTask](./valuetask/) | يوفر نتيجةً يمكن انتظارها لعملية غير متزامنة. |

## الدوال

| الدالة | الوصف |
| --- | --- |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**) | ينشئ مهمة تُكتمل بعد تأخير زمني. |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**, const [CancellationToken](../system.threading/cancellationtoken/)\&) | ينشئ مهمة تُكتمل بعد تأخير زمني ويمكن إلغاءها. |
| [TaskPtr](../system/taskptr/) [FromCanceled](./fromcanceled/)(const [CancellationToken](../system.threading/cancellationtoken/)\&) | ينشئ مهمة اكتملت بسبب الإلغاء بالرمز المحدد. |
| [TaskPtr](../system/taskptr/) [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | ينشئ مهمة اكتملت باستثناء محدد. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | ينشئ مهمة اكتملت باستثناء محدد ونوع نتيجة. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromResult](./fromresult/)(TResult) | ينشئ مهمة اكتملت بنجاح بالنتيجة المحددة. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&) | يضع العمل المحدد في قائمة الانتظار للتنفيذ في مجموعة الخيوط ويعيد مقبض [Task](./task/) لهذا العمل. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | يضع العمل المحدد في قائمة الانتظار للتنفيذ في مجموعة الخيوط ويعيد مقبض [Task](./task/) لهذا العمل. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Func](../system/func/)\<[TaskPtr](../system/taskptr/)\>\&) | يضع العمل المحدد في قائمة الانتظار للتنفيذ في مجموعة الخيوط ويعيد وكيلًا لـ [Task](./task/) الذي تُعيده الدالة. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [Run](./run/)(const [Func](../system/func/)\<TResult\>\&) | يضع العمل المحدد في قائمة الانتظار للتنفيذ في مجموعة الخيوط ويعيد مقبض Task<TResult> لهذا العمل. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | ينتظر حتى تكتمل جميع كائنات [Task](./task/) المقدمة. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | ينتظر حتى تكتمل جميع كائنات [Task](./task/) المقدمة. |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | ينتظر أيًا من كائنات [Task](./task/) المقدمة لتكتمل. |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | ينتظر أيًا من كائنات [Task](./task/) المقدمة لتكتمل. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | ينشئ مهمة ستكتمل عندما تكتمل جميع المهام المقدمة. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | ينشئ مهمة ستكتمل عندما تكتمل جميع المهام المقدمة. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | ينشئ مهمة ستكتمل عندما تكتمل جميع المهام المقدمة. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | ينشئ مهمة ستكتمل عندما تكتمل جميع المهام المقدمة. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | ينشئ مهمة ستكتمل عندما يكتمل أي من المهام المقدمة. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | ينشئ مهمة ستكتمل عندما يكتمل أي من المهام المقدمة. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | ينشئ مهمة ستكتمل عندما يكتمل أي من المهام المقدمة. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | ينشئ مهمة ستكتمل عندما يكتمل أي من المهام المقدمة. |
| [Runtime::CompilerServices::YieldAwaitable](../system.runtime.compilerservices/yieldawaitable/) [Yield](./yield/)() | ينشئ مهمة يمكن انتظارها تُعيد التحكم إلى السياق الحالي بشكل غير متزامن عند انتظارها. |

## التعدادات

| التعداد | الوصف |
| --- | --- |
| [TaskStatus](./taskstatus/) |  |