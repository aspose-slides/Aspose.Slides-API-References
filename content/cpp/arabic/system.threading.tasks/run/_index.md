---
title: Run()
second_title: دليل Aspose.Slides للـ C++ API
description: يضيف العمل المحدد إلى طابور مجموعة الخيوط للتنفيذ ويعيد مقبض Task لهذا العمل.
type: docs
weight: 157
url: /ar/system.threading.tasks/run/
---
## System::Threading::Tasks::Run(const Action<>\&) دالة


يضيف العمل المحدد إلى طابور مجموعة الخيوط للتنفيذ ويعيد مقبض [Task](../task/) لهذا العمل.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | العمل الذي يتم تنفيذه بشكل غير متزامن. |

### قيمة الإرجاع

[Task](../task/) يمثل العمل المضاف إلى طابور التنفيذ في مجموعة الخيوط.

## System::Threading::Tasks::Run(const Action<>\&, const CancellationToken\&) دالة


يضيف العمل المحدد إلى طابور مجموعة الخيوط للتنفيذ ويعيد مقبض [Task](../task/) لهذا العمل.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action, const CancellationToken &cancellationToken)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | العمل الذي يتم تنفيذه بشكل غير متزامن. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | رمز إلغاء يمكن استخدامه لإلغاء العمل إذا لم يبدأ بعد. |

### قيمة الإرجاع

[Task](../task/) يمثل العمل المضاف إلى طابور التنفيذ في مجموعة الخيوط.

## System::Threading::Tasks::Run(const Func\<TaskPtr\>\&) دالة


يضيف العمل المحدد إلى طابور مجموعة الخيوط ويُعيد وكيلًا لل[Task](../task/) الذي تُرجعه الدالة.

```cpp
TaskPtr System::Threading::Tasks::Run(const Func<TaskPtr> &function)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/)\>\& | العمل الذي يتم تنفيذه بشكل غير متزامن، والذي يُعيد [Task](../task/). |

### قيمة الإرجاع

[Task](../task/) يمثل وكيلًا لل[Task](../task/) الذي تُرجعه الدالة.

## System::Threading::Tasks::Run(const Func\<TResult\>\&) دالة


يضيف العمل المحدد إلى طابور مجموعة الخيوط ويعيد مقبض Task<TResult> لهذا العمل.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Run(const Func<TResult> &function)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TResult | نوع النتيجة التي تُرجعها المهمة. |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<TResult\>\& | العمل الذي يتم تنفيذه بشكل غير متزامن. |

### قيمة الإرجاع

Task<TResult> يمثل العمل المضاف إلى طابور التنفيذ في مجموعة الخيوط.

## انظر أيضًا

* تعريف نوع [TaskPtr](../../system/taskptr/)
* تعريف نوع [Action](../../system/action/)
* تعريف نوع [RTaskPtr](../../system/rtaskptr/)
* فئة [CancellationToken](../../system.threading/cancellationtoken/)
* فئة [Func](../../system/func/)
* نطاق [System::Threading::Tasks](../)
* مكتبة [Aspose.Slides](../../)