---
title: WaitAny()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: ينتظر أيًا من كائنات Task المقدمة لإكمال التنفيذ.
type: docs
weight: 183
url: /ar/system.threading.tasks/waitany/
---
## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) دالة

ينتظر أيًا من كائنات [Task](../task/) المقدمة لإكمال التنفيذ.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | مصفوفة من مثيلات [Task](../task/) التي سيتم الانتظار عليها. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | [CancellationToken](../../system.threading/cancellationtoken/) للمراقبة أثناء الانتظار حتى تكتمل المهام. |

### قيمة الإرجاع

فهرس المهمة المكتملة في مصفوفة المهام.

## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&) دالة

ينتظر أيًا من كائنات [Task](../task/) المقدمة لإكمال التنفيذ.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks)
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | مصفوفة من مثيلات [Task](../task/) التي سيتم الانتظار عليها. |

### قيمة الإرجاع

فهرس المهمة المكتملة في مصفوفة المهام.

## انظر أيضًا

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* فئة [CancellationToken](../../system.threading/cancellationtoken/)
* نطاق [System::Threading::Tasks](../)
* مكتبة [Aspose.Slides](../../)