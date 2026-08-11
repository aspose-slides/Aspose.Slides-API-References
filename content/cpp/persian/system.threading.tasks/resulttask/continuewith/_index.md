---
title: ContinueWith()
second_title: Aspose.Slides برای C++ مرجع API
description: یک ادامه ایجاد می‌کند که وقتی کار نتیجه‌ای پایان می‌یابد، اجرا می‌شود.
type: docs
weight: 40
url: /fa/system.threading.tasks/resulttask/continuewith/
---
## ResultTask::ContinueWith(const Action\<RTaskPtr\<T\>\>\&) method

Creates a continuation that executes when the result task completes.

```cpp
TaskPtr System::Threading::Tasks::ResultTask<T>::ContinueWith(const Action<RTaskPtr<T>> &continuationAction)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>\>\& | Action برای اجرا وقتی این کار تکمیل می‌شود، این کار نتیجه را دریافت می‌کند |

### مقدار بازگشت

TaskPtr یک کار جدید که نمایانگر ادامه است

## توضیحات

Action ادامه این [ResultTask](../) را دریافت می‌کند تا به مقدار نتیجه دسترسی پیدا کند

## ResultTask::ContinueWith(const Func\<RTaskPtr\<T\>, TNewResult\>\&) method

Creates a continuation that executes when the result task completes.

```cpp
template<typename TNewResult> RTaskPtr<TNewResult> System::Threading::Tasks::ResultTask<T>::ContinueWith(const Func<RTaskPtr<T>, TNewResult> &continuationFunction)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TNewResult | نوع نتیجه ادامه کار |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>, TNewResult\>\& | Function برای دریافت نتیجه ادامه زمانی که این کار تکمیل می‌شود و این کار نتیجه را دریافت می‌کند |

### مقدار بازگشت

RTaskPtr یک کار جدید که نمایانگر ادامه است

## توضیحات

Function ادامه این [ResultTask](../) را دریافت می‌کند تا به مقدار نتیجه دسترسی پیدا کند

## ResultTask::ContinueWith(const Action\<TaskPtr\>\&) method

Creates a continuation that executes when the task completes.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Action برای اجرا وقتی این کار تکمیل می‌شود |

### مقدار بازگشت

TaskPtr یک کار جدید که نمایانگر ادامه است

## ResultTask::ContinueWith(const Func\<TaskPtr, TResult\>\&) method

Creates a continuation that executes when the task completes.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TResult | یک نوع از نتیجهٔ کار |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Function برای دریافت نتیجه وقتی این کار تکمیل می‌شود |

### مقدار بازگشت

RTaskPtr یک کار جدید که نمایانگر ادامه است

## مراجعه کنید

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [ResultTask](../)
* Class [Func](../../../system/func/)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)