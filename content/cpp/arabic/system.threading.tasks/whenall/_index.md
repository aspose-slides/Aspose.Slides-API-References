---
title: WhenAll()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ مهمة ستكتمل عندما تنتهي جميع المهام المُزودة.
type: docs
weight: 196
url: /ar/system.threading.tasks/whenall/
---
## System::Threading::Tasks::WhenAll(const ArrayPtr\<TaskPtr\>\&) دالة

ينشئ مهمة ستكتمل عندما تنتهي جميع المهام المُزودة.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const ArrayPtr<TaskPtr> &tasks)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | المهام التي ينتظر إكمالها. |

### قيمة الإرجاع

مهمة تمثل إكمال جميع المهام المُزودة.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) دالة

ينشئ مهمة ستكتمل عندما تنتهي جميع المهام المُزودة.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | المهام التي ينتظر إكمالها. |

### قيمة الإرجاع

مهمة تمثل إكمال جميع المهام المُزودة.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) دالة

ينشئ مهمة ستكتمل عندما تنتهي جميع المهام المُزودة.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TResult | نوع نتائج المهام المكتملة. |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | المهام التي ينتظر إكمالها. |

### قيمة الإرجاع

مهمة تُرجع مصفوفة من جميع النتائج عندما تُكمل جميع المهام.

## System::Threading::Tasks::WhenAll(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) دالة

ينشئ مهمة ستكتمل عندما تنتهي جميع المهام المُزودة.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TResult | نوع نتائج المهام المكتملة. |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | المهام التي ينتظر إكمالها. |

### قيمة الإرجاع

مهمة تُرجع مصفوفة من جميع النتائج عندما تُكمل جميع المهام.

## انظر أيضًا

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)