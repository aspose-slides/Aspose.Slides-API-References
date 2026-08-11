---
title: Delay()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: ينشئ مهمة تُستكمل بعد تأخير زمني.
type: docs
weight: 105
url: /ar/system.threading.tasks/delay/
---
## System::Threading::Tasks::Delay(int32_t) دالة

ينشئ مهمة تكتمل بعد تأخير زمني.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay)
```

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | عدد المللي ثانية التي يجب الانتظار قبل إكمال المهمة المرجعة، أو -1 للانتظار إلى أجل غير مسمى. |

### قيمة الإرجاع

مهمة تمثل التأخير الزمني.

## System::Threading::Tasks::Delay(int32_t, const CancellationToken\&) دالة

ينشئ مهمة تكتمل بعد تأخير زمني ويمكن إلغاؤها.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay, const CancellationToken &cancellationToken)
```

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | عدد المللي ثانية التي يجب الانتظار قبل إكمال المهمة المرجعة، أو -1 للانتظار إلى أجل غير مسمى. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | رمز الإلغاء الذي يمكن استخدامه لإلغاء التأخير. |

### قيمة الإرجاع

مهمة تمثل التأخير الزمني.

## انظر أيضًا

* Typedef [TaskPtr](../../system/taskptr/)
* الفئة [CancellationToken](../../system.threading/cancellationtoken/)
* النطاق [System::Threading::Tasks](../)
* المكتبة [Aspose.Slides](../../)