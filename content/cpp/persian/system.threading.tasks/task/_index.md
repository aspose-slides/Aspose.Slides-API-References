---
title: Task
second_title: Aspose.Slides برای C++ مرجع API
description: نمایشی از یک عملیات ناهمزمان که می‌تواند منتظر بماند و با سایر تسک‌ها ترکیب شود.
type: docs
weight: 66
url: /fa/system.threading.tasks/task/
---
## کلاس Task

نمایش می‌دهد یک عملیات ناهمزمان که می‌تواند await شود و با سایر taskها ترکیب شود.

```cpp
class Task : public System::IDisposable
```

## متدها

| متد | توضیح |
| --- | --- |
| void [Activate](./activate/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | وظیفه را برای اجرا روی یک زمان‌بند فعال می‌کند. |
| void [AddCompletionAction](./addcompletionaction/)(const [Action](../../system/action/)<>\&) | عمل ادامه‌دهنده‌ای را که پس از اتمام اجرا می‌شود، اضافه می‌کند. |
| void [Cancel](./cancel/)() | وظیفه را به عنوان لغو‌شده علامت‌گذاری می‌کند و آن را به پایان می‌رساند. |
| void [Complete](./complete/)() | وظیفه را به عنوان تکمیل‌شده علامت‌گذاری می‌کند و آن را به پایان می‌رساند. |
| [Runtime::CompilerServices::ConfiguredTaskAwaitable](../../system.runtime.compilerservices/configuredtaskawaitable/) [ConfigureAwait](./configureawait/)(**bool**) const | رفتار awaitها بر روی این وظیفه را در رابطه با ضبط زمینه تنظیم می‌کند. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[TaskPtr](../../system/taskptr/)\>\&) | یک ادامه‌دهنده ایجاد می‌کند که پس از تکمیل وظیفه اجرا می‌شود. |
| [RTaskPtr](../../system/rtaskptr/)\<TResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/), TResult\>\&) | یک ادامه‌دهنده ایجاد می‌کند که پس از تکمیل وظیفه اجرا می‌شود. |
| void [Deactivate](./deactivate/)() | وظیفه را برای اجرا روی زمان‌بند فعلی‌اش (در صورت وجود) غیرفعال می‌کند. |
| void [Dispose](./dispose/)() override | منابع مرتبط با وظیفه را آزاد می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه‌شناسی به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه‌شناسی به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| void [Execute](./execute/)() | عملکرد وظیفه را اجرا می‌کند. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& [get_AsyncState](./get_asyncstate/)() const | شیء وضعیت تعریف‌شده توسط کاربر مرتبط با وظیفه را دریافت می‌کند. |
| static const [TaskPtr](../../system/taskptr/)\& [get_CompletedTask](./get_completedtask/)() | یک وظیفه تکمیل‌شده (تک‌نمونه) را دریافت می‌کند. |
| static [Nullable](../../system/nullable/)\<**int32_t**\> [get_CurrentId](./get_currentid/)() |  |
| [AggregateException](../../system/aggregateexception/) [get_Exception](./get_exception/)() const | شناسهٔ وظیفه را دریافت می‌کند. |
| **int32_t** [get_Id](./get_id/)() const |  |
| **bool** [get_IsCanceled](./get_iscanceled/)() const | اینکه آیا وظیفه به دلیل لغو تکمیل شده است را دریافت می‌کند. |
| **bool** [get_IsCompleted](./get_iscompleted/)() const | اینکه آیا وظیفه تکمیل شده است را دریافت می‌کند. |
| **bool** [get_IsFaulted](./get_isfaulted/)() const | اینکه آیا وظیفه به دلیل استثنای پردازش‌نشده تکمیل شده است را دریافت می‌کند. |
| const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\& [get_Scheduler](./get_scheduler/)() const | زمان‌بند مرتبط با این وظیفه را دریافت می‌کند. |
| [TaskStatus](../taskstatus/) [get_Status](./get_status/)() const | وضعیت جاری وظیفه را دریافت می‌کند. |
| [Runtime::CompilerServices::TaskAwaiter](../../system.runtime.compilerservices/taskawaiter/) [GetAwaiter](./getawaiter/)() const | یک awaiter برای این وظیفه جهت استفاده با Await دریافت می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ ارجاع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نمونه‌ای از متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. نمونه‌ای از فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. نمونه‌ای از عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری بیان lock() C# را پیاده‌سازی می‌کند. مستقیم صدا بزنید یا از شیء sentinel [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نمونه‌ای از متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان سازندهٔ کپی زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان سازندهٔ کپی زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr بر اساس ارجاع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ ارجاع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [RunSynchronously](./runsynchronously/)() | وظیفه را به صورت هم‌زمان روی رشتهٔ جاری اجرا می‌کند. |
| void [RunSynchronously](./runsynchronously/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | وظیفه را به صورت هم‌زمان با استفاده از زمان‌بند مشخص اجرا می‌کند. |
| void [set_Function](./set_function/)(const [FunctionT](./functiont/)\&) | تابع داخلی برای اجرا را تنظیم می‌کند. |
| void [set_Scheduler](./set_scheduler/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | زمان‌بند مرتبط با این وظیفه را تنظیم می‌کند. |
| void [set_Status](./set_status/)([TaskStatus](../taskstatus/)) | وضعیت وظیفه را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالبی nام را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید مستقیماً صدا زده شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش داده و برمی‌گرداند. نباید مستقیماً صدا زده شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [Start](./start/)() | اجرای وظیفه را با استفاده از زمان‌بند پیش‌فرض آغاز می‌کند. |
| void [Start](./start/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | اجرای وظیفه را با استفاده از زمان‌بند مشخص آغاز می‌کند. |
|  [Task](./task/)(const [Action](../../system/action/)<>\&) | یک [Task](./) را با عملی برای اجرا می‌سازد. |
|  [Task](./task/)(const [Action](../../system/action/)<>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | یک [Task](./) را با یک عمل و توکن لغو می‌سازد. |
|  [Task](./task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | یک [Task](./) را با عمل دارای حالت و شیء وضعیت می‌سازد. |
|  [Task](./task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | یک [Task](./) را با عمل دارای حالت، وضعیت، و توکن لغو می‌سازد. |
|  [Task](./task/)() | سازندهٔ داخلی برای ساختن وظایف بدون مقداردهی اولیه. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نمونه‌ای از متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری بیان lock() C# را باز می‌کند. مستقیم صدا بزنید یا از شیء sentinel [LockContext](../../system/lockcontext/) استفاده کنید. |
| void [Wait](./wait/)(const [CancellationToken](../../system.threading/cancellationtoken/)\&) | منتظر تکمیل وظیفه با پشتیبانی از لغو می‌ماند. |
| void [Wait](./wait/)() | منتظر تکمیل وظیفه می‌ماند. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید مستقیماً صدا زده شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید مستقیماً صدا زده شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |
|  [~Task](./~task/)() | منهدم. |

## تعاریف نوع

| تعریف نوع | توضیح |
| --- | --- |
| [FunctionT](./functiont/) | پیاده‌سازی داخلی. برای کد کاربر نیست. |

## ملاحظات

یک پیاده‌سازی C++ مشابه [System.Threading.Tasks.Task](./) در .NET فراهم می‌کند که از لغو، ادامه‌دهی‌ها، و الگوهای async/await پشتیبانی می‌کند 

## مراجع

* کلاس [IDisposable](../../system/idisposable/)
* فضای‌نام [System::Threading::Tasks](../)
* کتابخانه [Aspose.Slides](../../)