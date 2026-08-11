---
title: CancellationToken
second_title: Aspose.Slides لمرجع API C++
description: ينشر إشعارًا بأن العمليات يجب إلغاؤها. توفر هذه الفئة آلية للإلغاء التعاوني بين الخيوط، مما يسمح لخيط واحد بتنبيه الخيوط الأخرى بأن العملية يجب إلغاؤها.
type: docs
weight: 14
url: /ar/system.threading/cancellationtoken/
---
## فئة CancellationToken

ينشر إشعارًا بأن العمليات يجب إلغاؤها. توفر هذه الفئة آلية للإلغاء التعاوني بين الخيوط، مما يسمح لخيط واحد بتنبيه الخيوط الأخرى بأن العملية يجب إلغاؤها.

```cpp
class CancellationToken : public System::Details::BoxableObjectBase
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
|  [CancellationToken](./cancellationtoken/)() | منشئ افتراضي. |
| **bool** [get_CanBeCanceled](./get_canbecanceled/)() const | يعطي ما إذا كان هذا الرمز قادرًا على أن يكون في الحالة الملغاة. |
| **bool** [get_IsCancellationRequested](./get_iscancellationrequested/)() const | يعطي ما إذا تم طلب الإلغاء لهذا الرمز. |
| static [CancellationToken](./) [get_None](./get_none/)() | يرجع قيمة [System::Threading::CancellationToken](./) فارغة. |
| [CancellationTokenRegistration](../cancellationtokenregistration/) [Register](./register/)(const [Action](../../system/action/)<>\&) const | يسجّل رد اتصال سيتم استدعاؤه عند طلب الإلغاء. |
| void [ThrowIfCancellationRequested](./throwifcancellationrequested/)() const | يرمي استثناء OperationCanceledException إذا تم طلب الإلغاء. |

## ملاحظات

يمكن إلغاء [CancellationToken](./) فقط عبر [CancellationTokenSource](../cancellationtokensource/) المرتبط به.

## انظر أيضًا

* نطاق [System::Threading](../)
* مكتبة [Aspose.Slides](../../)