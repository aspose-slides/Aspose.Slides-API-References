---
title: Cancel()
second_title: Aspose.Slides لـ C++ مرجع API
description: يبلغ عن طلب الإلغاء.
type: docs
weight: 40
url: /ar/system.threading/cancellationtokensource/cancel/
---
## CancellationTokenSource::Cancel() طريقة


Communicates a request for cancellation.

```cpp
void System::Threading::CancellationTokenSource::Cancel()
```

## ملاحظات



سيتم استدعاء جميع ردود النداء المسجلة. 
ستُعيد الاستدعاءات اللاحقة إلى [get_IsCancellationRequested()](../get_iscancellationrequested/) قيمة true. 
يتم تنفيذ ردود النداء بشكل متزامن خلال هذا الاستدعاء. 

## انظر أيضًا

* فئة [CancellationTokenSource](../)
* نطاق [System::Threading](../../)
* مكتبة [Aspose.Slides](../../../)