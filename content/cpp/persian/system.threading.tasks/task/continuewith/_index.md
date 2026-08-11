---
title: ContinueWith()
second_title: مرجع API Aspose.Slides برای C++
description: یک ادامه ایجاد می‌کند که هنگام تکمیل کار اجرا می‌شود.
type: docs
weight: 118
url: /fa/system.threading.tasks/task/continuewith/
---
## Task::ContinueWith(const Action\<TaskPtr\>\&) متد

یک ادامه ایجاد می‌کند که هنگام تکمیل کار اجرا می‌شود.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Action برای اجرا وقتی این تسک کامل می‌شود |

### مقدار بازگشت

TaskPtr یک تسک جدید که نمایانگر ادامه است

## Task::ContinueWith(const Func\<TaskPtr, TResult\>\&) متد

یک ادامه ایجاد می‌کند که هنگام تکمیل کار اجرا می‌شود.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TResult | نوعی از نتیجهٔ کار |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Function برای دریافت نتیجه وقتی این تسک کامل می‌شود |

### مقدار بازگشت

RTaskPtr یک تسک جدید که نمایانگر ادامه است

## موارد مرتبط

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [Task](../)
* Class [Func](../../../system/func/)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)