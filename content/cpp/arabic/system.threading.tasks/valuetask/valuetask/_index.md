---
title: ValueTask()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بإنشاء ValueTask فارغ غير مهيأ.
type: docs
weight: 1
url: /ar/system.threading.tasks/valuetask/valuetask/
---
## ValueTask::ValueTask() منشئ

يقوم بإنشاء [ValueTask](../) فارغ غير مهيأ.

```cpp
System::Threading::Tasks::ValueTask::ValueTask()
```

## ملاحظات

المهمة غير مكتملة ولا تحتوي على أي نتيجة. محاولة الحصول على النتيجة ستؤدي إلى إطلاق استثناء.

## ValueTask::ValueTask(const TaskPtr\&) منشئ

يقوم بإنشاء [ValueTask](../) من مؤشر مشترك إلى [Task](../../task/).

```cpp
System::Threading::Tasks::ValueTask::ValueTask(const TaskPtr &task)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| task | const [TaskPtr](../../../system/taskptr/)\& | المهمة لتغليفها. يمكن أن تكون null لمهمة فارغة. |

## ملاحظات

سيقوم [ValueTask](../) بتمثيل حالة المهمة المقدمة.

## انظر أيضًا

* تعريف نوع [TaskPtr](../../../system/taskptr/)
* فئة [ValueTask](../)
* مساحة الاسم [System::Threading::Tasks](../../)
* مكتبة [Aspose.Slides](../../../)