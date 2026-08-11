---
title: WaitAll()
second_title: Aspose.Slides للـ C++ مرجع API
description: ينتظر إكمال تنفيذ جميع كائنات Task المقدمة.
type: docs
weight: 170
url: /ar/system.threading.tasks/waitall/
---
## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) دالة

ينتظر إكمال تنفيذ جميع الكائنات [Task](../task/) المقدمة.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | مصفوفة من مثيلات [Task](../task/) التي ينتظرها. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | [CancellationToken](../../system.threading/cancellationtoken/) لملاحظته أثناء انتظار إكمال tasks. |

## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&) دالة

ينتظر إكمال تنفيذ جميع الكائنات [Task](../task/) المقدمة.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | مصفوفة من مثيلات [Task](../task/) التي ينتظرها. |

## انظر أيضًا

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* فئة [CancellationToken](../../system.threading/cancellationtoken/)
* مساحة الاسم [System::Threading::Tasks](../)
* مكتبة [Aspose.Slides](../../)