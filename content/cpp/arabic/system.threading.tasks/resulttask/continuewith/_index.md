---
title: ContinueWith()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ متابعة تُنفّذ عند إكمال مهمة النتيجة.
type: docs
weight: 40
url: /ar/system.threading.tasks/resulttask/continuewith/
---
## ResultTask::ContinueWith(const Action\<RTaskPtr\<T\>\>\&) طريقة

ينشئ عملية متابعة تُنفّذ عند اكتمال مهمة النتيجة.

```cpp
TaskPtr System::Threading::Tasks::ResultTask<T>::ContinueWith(const Action<RTaskPtr<T>> &continuationAction)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>\>\& | الإجراء الذي يُنفّذ عند اكتمال هذه المهمة، مستلمًا مهمة النتيجة هذه |

### قيمة الإرجاع

TaskPtr مهمة جديدة تمثل المتابعة

## ملاحظات

تستقبل عملية المتابعة هذا [ResultTask](../) للوصول إلى قيمة النتيجة

## ResultTask::ContinueWith(const Func\<RTaskPtr\<T\>, TNewResult\>\&) طريقة

ينشئ عملية متابعة تُنفّذ عند اكتمال مهمة النتيجة.

```cpp
template<typename TNewResult> RTaskPtr<TNewResult> System::Threading::Tasks::ResultTask<T>::ContinueWith(const Func<RTaskPtr<T>, TNewResult> &continuationFunction)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TNewResult | نوع النتيجة لمتابعة المهمة |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>, TNewResult\>\& | الدالة للحصول على نتيجة المتابعة عندما تكتمل هذه المهمة، مستلمًا مهمة النتيجة هذه |

### قيمة الإرجاع

RTaskPtr مهمة جديدة تمثل المتابعة

## ملاحظات

تستقبل الدالة المتابعة هذا [ResultTask](../) للوصول إلى قيمة النتيجة

## ResultTask::ContinueWith(const Action\<TaskPtr\>\&) طريقة

ينشئ عملية متابعة تُنفّذ عند اكتمال المهمة.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | الإجراء الذي يُنفّذ عند اكتمال هذه المهمة |

### قيمة الإرجاع

TaskPtr مهمة جديدة تمثل المتابعة

## ResultTask::ContinueWith(const Func\<TaskPtr, TResult\>\&) طريقة

ينشُئ عملية متابعة تُنفّذ عند اكتمال المهمة.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TResult | نوع نتيجة المهمة |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | الدالة للحصول على النتيجة عندما تكتمل هذه المهمة |

### قيمة الإرجاع

RTaskPtr مهمة جديدة تمثل المتابعة

## انظر أيضاً

* تعريف نوع [TaskPtr](../../../system/taskptr/)
* تعريف نوع [Action](../../../system/action/)
* تعريف نوع [RTaskPtr](../../../system/rtaskptr/)
* فئة [ResultTask](../)
* فئة [Func](../../../system/func/)
* مساحة الاسم [System::Threading::Tasks](../../)
* مكتبة [Aspose.Slides](../../../)