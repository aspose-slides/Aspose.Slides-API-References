---
title: "System::Threading::Tasks"
second_title: Aspose.Slides برای C++ مرجع API
description: 
type: docs
weight: 1015
url: /fa/system.threading.tasks/
---
## کلاس‌ها

| کلاس | توضیح |
| --- | --- |
| [Parallel](./parallel/) | پشتیبانی از حلقه‌ها و نواحی موازی را فراهم می‌کند. |
| [ParallelLoopResult](./parallelloopresult/) | وضعیت تکمیل یک حلقه [Parallel](./parallel/) را فراهم می‌کند. |
| [ParallelOptions](./paralleloptions/) | گزینه‌هایی را که رفتار متدهای کلاس [Parallel](./parallel/) را پیکربندی می‌کنند ذخیره می‌کند. |
| [ResultTask](./resulttask/) | یک تخصص [Task](./task/) که پس از تکمیل، مقدار نتیجه را برمی‌گرداند. |
| [ResultValueTask](./resultvaluetask/) | نوعی شبیه به کار را نشان می‌دهد که می‌تواند یا مقدار نتیجه مستقیم یا ResultTask<T> را بپیچاند. |
| [Task](./task/) | عملیات ناهمزمانی را نشان می‌دهد که می‌تواند صبر شود و با کارهای دیگر ترکیب شود. |
| [TaskScheduler](./taskscheduler/) | شیئی را نشان می‌دهد که کار سطح پایین صف‌گذاری کارها بر روی رشته‌ها را مدیریت می‌کند. |
| [ValueTask](./valuetask/) | نتیجه‌ای قابل انتظار از یک عملیات ناهمزمان را فراهم می‌کند. |

## توابع

| تابع | توضیح |
| --- | --- |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**) | کاری را ایجاد می‌کند که پس از یک تأخیر زمانی تکمیل می‌شود. |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**, const [CancellationToken](../system.threading/cancellationtoken/)\&) | کاری را ایجاد می‌کند که پس از یک تأخیر زمانی تکمیل می‌شود و می‌تواند لغو شود. |
| [TaskPtr](../system/taskptr/) [FromCanceled](./fromcanceled/)(const [CancellationToken](../system.threading/cancellationtoken/)\&) | کاری را ایجاد می‌کند که به دلیل لغو با توکن مشخص، تکمیل شده است. |
| [TaskPtr](../system/taskptr/) [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | کاری را ایجاد می‌کند که با یک استثنای مشخص تکمیل شده است. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | کاری را ایجاد می‌کند که با یک استثنای مشخص و نوع نتیجه مشخص تکمیل شده است. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromResult](./fromresult/)(TResult) | کاری را ایجاد می‌کند که با موفقیت با نتیجهٔ مشخص تکمیل شده است. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&) | کار مشخص‌شده را برای اجرا در مجموعهٔ رشته‌ها صف می‌کند و یک دستگیرهٔ [Task](./task/) برای آن کار برمی‌گرداند. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | کار مشخص‌شده را برای اجرا در مجموعهٔ رشته‌ها صف می‌کند و یک دستگیرهٔ [Task](./task/) برای آن کار برمی‌گرداند. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Func](../system/func/)\<[TaskPtr](../system/taskptr/)\>\&) | کار مشخص‌شده را برای اجرا در مجموعهٔ رشته‌ها صف می‌کند و یک پروکسی برای [Task](./task/) برگردانده‌شده توسط تابع فراهم می‌کند. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [Run](./run/)(const [Func](../system/func/)\<TResult\>\&) | کار مشخص‌شده را برای اجرا در مجموعهٔ رشته‌ها صف می‌کند و یک دستگیرهٔ Task<TResult> برای آن کار برمی‌گرداند. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | تا تمام اشیاء [Task](./task/) ارائه شده، اجرا را تکمیل کنند، صبر می‌کند. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | تا تمام اشیاء [Task](./task/) ارائه شده، اجرا را تکمیل کنند، صبر می‌کند. |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | تا هر یک از اشیاء [Task](./task/) ارائه شده، اجرا را تکمیل کنند، صبر می‌کند. |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | تا هر یک از اشیاء [Task](./task/) ارائه شده، اجرا را تکمیل کنند، صبر می‌کند. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | کاری را ایجاد می‌کند که زمانی که تمام کارهای ارسال‌شده تکمیل شوند، به پایان می‌رسد. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | کاری را ایجاد می‌کند که زمانی که تمام کارهای ارسال‌شده تکمیل شوند، به پایان می‌رسد. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | کاری را ایجاد می‌کند که زمانی که تمام کارهای ارسال‌شده تکمیل شوند، به پایان می‌رسد. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | کاری را ایجاد می‌کند که زمانی که تمام کارهای ارسال‌شده تکمیل شوند، به پایان می‌رسد. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | کاری را ایجاد می‌کند که وقتی هر یک از کارهای ارسال‌شده تکمیل شوند، به پایان می‌رسد. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | کاری را ایجاد می‌کند که وقتی هر یک از کارهای ارسال‌شده تکمیل شوند، به پایان می‌رسد. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | کاری را ایجاد می‌کند که وقتی هر یک از کارهای ارسال‌شده تکمیل شوند، به پایان می‌رسد. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | کاری را ایجاد می‌کند که وقتی هر یک از کارهای ارسال‌شده تکمیل شوند، به پایان می‌رسد. |
| [Runtime::CompilerServices::YieldAwaitable](../system.runtime.compilerservices/yieldawaitable/) [Yield](./yield/)() | کاری قابل انتظار ایجاد می‌کند که هنگام انتظار به‌صورت ناهمزمان به زمینهٔ جاری باز می‌گردد. |

## شمارش‌ها

| شمارش | توضیح |
| --- | --- |
| [TaskStatus](./taskstatus/) |  |