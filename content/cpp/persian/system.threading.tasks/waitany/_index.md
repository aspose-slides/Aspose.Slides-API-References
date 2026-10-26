---
title: WaitAny()
second_title: مرجع API Aspose.Slides برای C++
description: برای تکمیل اجرای هر یک از اشیای Task ارائه‌شده منتظر می‌ماند.
type: docs
weight: 183
url: /fa/system.threading.tasks/waitany/
---
## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) تابع

برای اتمام اجرای هر یک از اشیای ارائه‌شده [Task](../task/) صبر می‌کند.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | یک آرایه از نمونه‌های [Task](../task/) که باید صبر کرد. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | یک [CancellationToken](../../system.threading/cancellationtoken/) برای مشاهده در حین صبر برای تکمیل کارها. |

### مقدار بازگشت

ایندکس کار تکمیل‌شده در آرایهٔ کارها.

## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&) تابع

برای اتمام اجرای هر یک از اشیای ارائه‌شده [Task](../task/) صبر می‌کند.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | یک آرایه از نمونه‌های [Task](../task/) که باید صبر کرد. |

### مقدار بازگشت

ایندکس کار تکمیل‌شده در آرایهٔ کارها.

## موارد مرتبط

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* کلاس [CancellationToken](../../system.threading/cancellationtoken/)
* فضای‌نام [System::Threading::Tasks](../)
* کتابخانه [Aspose.Slides](../../)