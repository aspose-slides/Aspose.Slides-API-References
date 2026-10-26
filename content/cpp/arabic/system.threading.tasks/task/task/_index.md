---
title: Task()
second_title: Aspose.Slides لمرجع API لـ C++
description: يقوم بإنشاء Task مع إجراء لتنفيذه.
type: docs
weight: 1
url: /ar/system.threading.tasks/task/task/
---
## Task::Task(const Action<>\&) مُنشئ

يقوم بإنشاء [Task](../) مع إجراء لتنفيذه.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | الإجراء لتنفيذه بشكل غير متزامن |

## Task::Task(const Action<>\&, const CancellationToken\&) مُنشئ

يقوم بإنشاء [Task](../) مع إجراء ورمز إلغاء.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action, const CancellationToken &cancellationToken)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | الإجراء لتنفيذه بشكل غير متزامن |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | الرمز لمراقبة طلبات الإلغاء |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\>) مُنشئ

يقوم بإنشاء [Task](../) مع إجراء يحتوي على حالة وكائن حالة.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | الإجراء لتنفيذه (يقبل كائن الحالة) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | كائن الحالة المعرّف من قبل المستخدم المرسل إلى الإجراء |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&, const CancellationToken\&) مُنشئ

يقوم بإنشاء [Task](../) مع إجراء يحتوي على حالة، وحالة، ورمز إلغاء.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state, const CancellationToken &cancellationToken)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | الإجراء لتنفيذه (يقبل كائن الحالة) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | كائن الحالة المعرّف من قبل المستخدم المرسل إلى الإجراء |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | الرمز لمراقبة طلبات الإلغاء |

## Task::Task() مُنشئ

منشئ داخلي لإنشاء مهام غير مهيأة.

```cpp
System::Threading::Tasks::Task::Task()
```

## انظر أيضًا

* تعريف نوع [Action](../../../system/action/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Task](../)
* فئة [CancellationToken](../../../system.threading/cancellationtoken/)
* فئة [Object](../../../system/object/)
* مساحة اسم [System::Threading::Tasks](../../)
* مكتبة [Aspose.Slides](../../../)