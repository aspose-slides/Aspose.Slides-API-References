---
title: ResultTask()
second_title: مرجع Aspose.Slides for C++ API
description: ينشئ ResultTask باستخدام دالة تُعيد قيمة.
type: docs
weight: 1
url: /ar/system.threading.tasks/resulttask/resulttask/
---
## ResultTask::ResultTask(const Func\<T\>\&) المُنشئ

ينشئ [ResultTask](../) باستخدام دالة تُعيد قيمة.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const Func<T> &function)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| function | const [Func](../../../system/func/)\<T\>\& | الدالة التي تُنفّذ بشكل غير متزامن وتُعيد نتيجة |

## ResultTask::ResultTask() المُنشئ

تنفيذ داخلي. ليس لاستخدام المستخدم.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask()
```

## ملاحظات

منشئ داخلي لإنشاء مهام نتيجة غير مهيأة

## ResultTask::ResultTask(const T\&) المُنشئ

منشئ داخلي لإنشاء مهام نتيجة بالنتيجة المحددة.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const T &result)
```

## انظر أيضًا

* الفئة [Func](../../../system/func/)
* الفئة [ResultTask](../)
* النطاق [System::Threading::Tasks](../../)
* المكتبة [Aspose.Slides](../../../)