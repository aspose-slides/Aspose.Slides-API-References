---
title: WaitAll()
second_title: مرجع API Aspose.Slides برای C++
description: صبر می‌کند تا تمام اشیاء Task ارائه‌شده به اتمام اجرا برسند.
type: docs
weight: 170
url: /fa/system.threading.tasks/waitall/
---
## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) تابع

صبر می‌کند تا تمام اشیاء [Task](../task/) ارائه‌شده به اتمام اجرا برسند.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | یک آرایه از نمونه‌های [Task](../task/) که باید منتظر آن‌ها بود. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | یک [CancellationToken](../../system.threading/cancellationtoken/) برای مشاهده در حین صبر برای تکمیل کارها. |

## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&) تابع

صبر می‌کند تا تمام اشیاء [Task](../task/) ارائه‌شده به اتمام اجرا برسند.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks)
```

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | یک آرایه از نمونه‌های [Task](../task/) که باید منتظر آن‌ها بود. |

## موارد مرتبط

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* کلاس [CancellationToken](../../system.threading/cancellationtoken/)
* فضای نام [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)