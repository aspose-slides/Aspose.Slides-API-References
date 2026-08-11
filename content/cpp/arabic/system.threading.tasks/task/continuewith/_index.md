---
title: ContinueWith()
second_title: Aspose.Slides للـ C++ مرجع API
description: ينشئ استمرارًا يتم تنفيذه عند إكمال المهمة.
type: docs
weight: 118
url: /ar/system.threading.tasks/task/continuewith/
---
## Task::ContinueWith(const Action\<TaskPtr\>\&) طريقة

ينشئ استمرارًا يتم تنفيذه عند إكمال المهمة.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```

### المعاملات

| معلمة | نوع | وصف |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Action لتنفيذ عندما تكتمل هذه المهمة |

### قيمة الإرجاع

TaskPtr مهمة جديدة تمثل الاستمرار

## Task::ContinueWith(const Func\<TaskPtr, TResult\>\&) طريقة

ينشئ استمرارًا يتم تنفيذه عند إكمال المهمة.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```

### معلمات القالب

| معلمة | وصف |
| --- | --- |
| TResult | نوع نتيجة المهمة |

### المعاملات

| معلمة | نوع | وصف |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Function للحصول على النتيجة عندما تكتمل هذه المهمة |

### قيمة الإرجاع

RTaskPtr مهمة جديدة تمثل الاستمرار

## انظر أيضًا

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* فئة [Task](../)
* فئة [Func](../../../system/func/)
* فضاء الاسم [System::Threading::Tasks](../../)
* مكتبة [Aspose.Slides](../../../)