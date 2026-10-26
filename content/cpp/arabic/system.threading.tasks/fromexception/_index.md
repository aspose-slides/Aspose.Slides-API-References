---
title: FromException()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: ينشئ مهمة تم إكمالها باستثناء محدد.
type: docs
weight: 131
url: /ar/system.threading.tasks/fromexception/
---
## System::Threading::Tasks::FromException(const Exception\&) دالة

ينشئ مهمة تم الانتهاء منها باستثناء محدد.

```cpp
TaskPtr System::Threading::Tasks::FromException(const Exception &exception)
```

### وسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | الاستثناء الذي يتم إكمال المهمة به. |

### قيمة الإرجاع

مهمة معطوبة.

## System::Threading::Tasks::FromException(const Exception\&) دالة

ينشئ مهمة تم الانتهاء منها باستثناء محدد ونوع النتيجة.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromException(const Exception &exception)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TResult | نوع نتيجة المهمة. |

### وسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | الاستثناء الذي يتم إكمال المهمة به. |

### قيمة الإرجاع

مهمة معطوبة بالنوع المحدد للنتيجة.

## أنظر أيضاً

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Exception](../../system/exception/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)