---
title: ValueTask()
second_title: Aspose.Slides برای مرجع API C++
description: یک ValueTask خالی و بدون مقدار اولیه می‌سازد.
type: docs
weight: 1
url: /fa/system.threading.tasks/valuetask/valuetask/
---
## ValueTask::ValueTask() سازنده

یک [ValueTask](../) خالی و بدون مقدار اولیه می‌سازد.

```cpp
System::Threading::Tasks::ValueTask::ValueTask()
```

## توضیحیات

کار انجام نشده است و هیچ نتیجه‌ای ندارد. تلاش برای دریافت نتیجه منجر به پرتاب استثنا می‌شود.

## ValueTask::ValueTask(const TaskPtr\&) سازنده

یک [ValueTask](../) را از یک اشاره‌گر اشتراکی به [Task](../../task/) می‌سازد.

```cpp
System::Threading::Tasks::ValueTask::ValueTask(const TaskPtr &task)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| task | const [TaskPtr](../../../system/taskptr/)\& | کار برای بسته‌بندی. می‌تواند برای یک کار خالی مقدار null باشد. |

## توضیحیات

[ValueTask](../) وضعیت کار ارائه‌شده را نشان می‌دهد.

## موارد مرتبط
* Typedef [TaskPtr](../../../system/taskptr/)
* Class [ValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)