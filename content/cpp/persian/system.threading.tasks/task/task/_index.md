---
title: Task()
second_title: Aspose.Slides برای C++ مرجع API
description: یک Task را با عملی برای اجرا می‌سازد.
type: docs
weight: 1
url: /fa/system.threading.tasks/task/task/
---
## Task::Task(const Action<>\&) سازنده

یک [Task](../) را با عملی برای اجرا می‌سازد.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | عملی که به طور ناهمزمان اجرا می‌شود |

## Task::Task(const Action<>\&, const CancellationToken\&) سازنده

یک [Task](../) را با یک عمل و توکن لغو می‌سازد.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action, const CancellationToken &cancellationToken)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | عملی که به طور ناهمزمان اجرا می‌شود |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | توکنی برای نظارت بر درخواست‌های لغو |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&) سازنده

یک [Task](../) را با عملی حالت‌دار و شیء وضعیت می‌سازد.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | عملی که اجرا می‌شود (شیء وضعیت را می‌پذیرد) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | شیء وضعیت تعریف‌شده توسط کاربر که به عمل پاس داده می‌شود |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&, const CancellationToken\&) سازنده

یک [Task](../) را با عمل حالت‌دار، وضعیت و توکن لغو می‌سازد.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state, const CancellationToken &cancellationToken)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | عملی که اجرا می‌شود (شیء وضعیت را می‌پذیرد) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | شیء وضعیت تعریف‌شده توسط کاربر که به عمل پاس داده می‌شود |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | توکنی برای نظارت بر درخواست‌های لغو |

## Task::Task() سازنده

سازنده داخلی برای ایجاد وظایف بدون مقدار اولیه.

```cpp
System::Threading::Tasks::Task::Task()
```

## همچنین ببینید

* تعریف‌نوع [Action](../../../system/action/)
* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Task](../)
* کلاس [CancellationToken](../../../system.threading/cancellationtoken/)
* کلاس [Object](../../../system/object/)
* فضای‌نام [System::Threading::Tasks](../../)
* کتابخانه [Aspose.Slides](../../../)