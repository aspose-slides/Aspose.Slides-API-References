---
title: RunSynchronously()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينفّذ المهمة بشكل متزامن على الخيط الحالي.
type: docs
weight: 157
url: /ar/system.threading.tasks/task/runsynchronously/
---
## Task::RunSynchronously() method

ينفّذ المهمة بشكل متزامن على الخيط الحالي.

```cpp
void System::Threading::Tasks::Task::RunSynchronously()
```

## Task::RunSynchronously(const SharedPtr\<TaskScheduler\>\&) method

ينفّذ المهمة بشكل متزامن باستخدام المجدول المحدد.

```cpp
void System::Threading::Tasks::Task::RunSynchronously(const SharedPtr<TaskScheduler> &scheduler)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| scheduler | const [SharedPtr](../../../system/sharedptr/)\<[TaskScheduler](../../taskscheduler/)\>\& | المجدول المستخدم للتنفيذ |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [Task](../)
* الفئة [TaskScheduler](../../taskscheduler/)
* النطاق [System::Threading::Tasks](../../)
* المكتبة [Aspose.Slides](../../../)