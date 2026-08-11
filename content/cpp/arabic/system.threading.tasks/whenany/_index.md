---
title: WhenAny()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينشئ مهمة ستكتمل عندما تنتهي أي من المهام المقدمة.
type: docs
weight: 209
url: /ar/system.threading.tasks/whenany/
---
## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) دالة

ينشئ مهمة ستكتمل عندما تنتهي أي من المهام المقدمة.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | المهام التي يُنتظر إكمالها. |

### قيمة الإرجاع

مهمة تمثل إكمال إحدى المهام المقدمة.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<TaskPtr\>\&) دالة

ينشئ مهمة ستكتمل عندما تنتهي أي من المهام المقدمة.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const ArrayPtr<TaskPtr> &tasks)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | المهام التي يُنتظر إكمالها. |

### قيمة الإرجاع

مهمة تمثل إكمال إحدى المهام المقدمة.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) دالة

ينشئ مهمة ستكتمل عندما تنتهي أي من المهام المقدمة.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TResult | نوع نتيجة المهمة المكتملة. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | المهام التي يُنتظر إكمالها. |

### قيمة الإرجاع

مهمة تُعيد أول مهمة مكتملة عند إكمال أي مهمة.

## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) دالة

ينشئ مهمة ستكتمل عندما تنتهي أي من المهام المقدمة.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TResult | نوع نتيجة المهمة المكتملة. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | المهام التي يُنتظر إكمالها. |

### قيمة الإرجاع

مهمة تُعيد أول مهمة مكتملة عند إكمال أي مهمة.

## انظر أيضاً

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* الفئة [IEnumerable](../../system.collections.generic/ienumerable/)
* فضاء الاسم [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)