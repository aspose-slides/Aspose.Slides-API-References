---
title: Run()
second_title: Aspose.Slides برای C++ مرجع API
description: کار مشخص‌شده را برای اجرا در استخر رشته‌ها صف می‌کند و یک دستگیره Task برای آن کار برمی‌گرداند.
type: docs
weight: 157
url: /fa/system.threading.tasks/run/
---
## System::Threading::Tasks::Run(const Action<>\&) تابع

کار مشخص‌شده را برای اجرا در استخر رشته‌ها صف می‌کند و یک دستگیره [Task](../task/) برای آن کار برمی‌گرداند.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | کاری که به‌صورت ناهمزمان اجرا می‌شود. |

### مقدار بازگشتی

یک [Task](../task/) که نمایانگر کاری است که برای اجرا در استخر رشته‌ها صف‌بندی شده است.

## System::Threading::Tasks::Run(const Action<>\&, const CancellationToken\&) تابع

کار مشخص‌شده را برای اجرا در استخر رشته‌ها صف می‌کند و یک دستگیره [Task](../task/) برای آن کار برمی‌گرداند.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action, const CancellationToken &cancellationToken)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | کاری که به‌صورت ناهمزمان اجرا می‌شود. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | توکن لغوی که می‌توان از آن برای لغو کار استفاده کرد اگر هنوز شروع نشده باشد. |

### مقدار بازگشتی

یک [Task](../task/) که نمایانگر کاری است که برای اجرا در استخر رشته‌ها صف‌بندی شده است.

## System::Threading::Tasks::Run(const Func\<TaskPtr\>\&) تابع

کار مشخص‌شده را برای اجرا در استخر رشته‌ها صف می‌کند و یک پراکسی برای [Task](../task/) بازگردانده‌شده توسط تابع برمی‌گرداند.

```cpp
TaskPtr System::Threading::Tasks::Run(const Func<TaskPtr> &function)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/)\>\& | کاری که به‌صورت ناهمزمان اجرا می‌شود و یک [Task](../task/) باز می‌گرداند. |

### مقدار بازگشتی

یک [Task](../task/) که نمایانگر پراکسی برای [Task](../task/) بازگردانده شده توسط تابع است.

## System::Threading::Tasks::Run(const Func\<TResult\>\&) تابع

کار مشخص‌شده را برای اجرا در استخر رشته‌ها صف می‌کند و یک دستگیره Task<TResult> برای آن کار برمی‌گرداند.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Run(const Func<TResult> &function)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TResult | نوع نتیجه بازگردانده‌شده توسط کار. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<TResult\>\& | کاری که به‌صورت ناهمزمان اجرا می‌شود. |

### مقدار بازگشتی

یک Task<TResult> که نمایانگر کاری است که برای اجرا در استخر رشته‌ها صف‌بندی شده است.

## موارد مرتبط

* تعریف نوع [TaskPtr](../../system/taskptr/)
* تعریف نوع [Action](../../system/action/)
* تعریف نوع [RTaskPtr](../../system/rtaskptr/)
* کلاس [CancellationToken](../../system.threading/cancellationtoken/)
* کلاس [Func](../../system/func/)
* فضای نام [System::Threading::Tasks](../)
* کتابخانه [Aspose.Slides](../../)