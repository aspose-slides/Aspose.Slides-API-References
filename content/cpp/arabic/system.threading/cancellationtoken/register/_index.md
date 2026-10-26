---
title: Register()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يسجل رد اتصال سيتم استدعاؤه عند طلب الإلغاء.
type: docs
weight: 40
url: /ar/system.threading/cancellationtoken/register/
---
## CancellationToken::Register(const Action<>\&) const طريقة

يسجل رد اتصال سيتم استدعاؤه عند طلب الإلغاء.

```cpp
CancellationTokenRegistration System::Threading::CancellationToken::Register(const Action<> &callback) const
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| callback | const [Action](../../../system/action/)<>\& | الإجراء Action<> للتنفيذ عند طلب الإلغاء. |

### قيمة الإرجاع

كائن [CancellationTokenRegistration](../../cancellationtokenregistration/) يمكن استخدامه لإلغاء تسجيل رد الاتصال.

## ملاحظات

إذا تم طلب الإلغاء مسبقًا، سيتم استدعاء رد الاتصال فورًا. 

يجب أن يكون رد الاتصال قصير العمر وغير محجوب لأنه سيتم تنفيذه على الخيط الذي يستدعي Cancel() على الـ [CancellationTokenSource](../../cancellationtokensource/).

## انظر أيضاً

* تعريف نوع [Action](../../../system/action/)
* فئة [CancellationTokenRegistration](../../cancellationtokenregistration/)
* فئة [CancellationToken](../)
* مساحة الاسم [System::Threading](../../)
* مكتبة [Aspose.Slides](../../../)