---
title: SetSynchronizationContext()
second_title: مرجع API Aspose.Slides للغة C++
description: يضبط سياق المزامنة للخيط الحالي.
type: docs
weight: 53
url: /ar/system.threading/synchronizationcontext/setsynchronizationcontext/
---
## SynchronizationContext::SetSynchronizationContext(const SharedPtr\<SynchronizationContext\>\&) method

يضبط سياق المزامنة للخيط الحالي.

```cpp
static void System::Threading::SynchronizationContext::SetSynchronizationContext(const SharedPtr<SynchronizationContext> &syncContext)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| syncContext | const [SharedPtr](../../../system/sharedptr/)\<[SynchronizationContext](../)\>\& | سياق المزامنة الذي سيتم تعيينه للخيط الحالي. |
## ملاحظات

تمرير nullptr سيزيل سياق المزامنة للخيط الحالي.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [SynchronizationContext](../)
* نطاق الاسم [System::Threading](../../)
* مكتبة [Aspose.Slides](../../../)