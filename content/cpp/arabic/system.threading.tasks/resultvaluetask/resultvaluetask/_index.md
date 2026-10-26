---
title: ResultValueTask()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ ResultValueTask فارغًا غير مهيأ.
type: docs
weight: 1
url: /ar/system.threading.tasks/resultvaluetask/resultvaluetask/
---
## ResultValueTask::ResultValueTask() مُنشئ

ينشئ [ResultValueTask](../) فارغًا غير مهيأ.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask()
```

## ملاحظات

المهمة غير مكتملة ولا تحتوي على نتيجة. محاولة الحصول على النتيجة ستؤدي إلى رمي استثناء.

## ResultValueTask::ResultValueTask(const T&) مُنشئ

ينشئ [ResultValueTask](../) مكتملًا بالنتيجة المحددة.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const T &result)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| result | const T& | القيمة التي تُغلف في مهمة مكتملة. |

## ملاحظات

هذا ينشئ مهمة مكتملة بنجاح تُعيد القيمة فورًا.

## ResultValueTask::ResultValueTask(const RTaskPtr<T>&) مُنشئ

ينشئ [ResultValueTask](../) من مؤشر مشترك إلى ResultTask<T>.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const RTaskPtr<T> &task)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| task | const [RTaskPtr](../../../system/rtaskptr/)<T>& | المهمة التي تُغلف. يمكن أن تكون فارغة لمهمة فارغة. |

## ملاحظات

سيمثل [ResultValueTask](../) حالة ونتيجة المهمة المقدمة.

## انظر أيضاً

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* فئة [ResultValueTask](../)
* نطاق [System::Threading::Tasks](../../)
* مكتبة [Aspose.Slides](../../../)