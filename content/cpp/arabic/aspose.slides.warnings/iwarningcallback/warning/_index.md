---
title: Warning()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: طريقة رد الاتصال التي تستقبل التحذير وتقرر ما إذا كان يجب إلغاء العملية.
type: docs
weight: 1
url: /ar/aspose.slides.warnings/iwarningcallback/warning/
---
## IWarningCallback::Warning(System::SharedPtr\<IWarningInfo\>) طريقة

طريقة رد الاتصال التي تستقبل التحذير وتقرر ما إذا كان يجب إلغاء العملية.

```cpp
virtual ReturnAction Aspose::Slides::Warnings::IWarningCallback::Warning(System::SharedPtr<IWarningInfo> warning)=0
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| warning | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningInfo](../../iwarninginfo/)\> | التحذير للمعالجة. |

### قيمة الإرجاع

قرار الإلغاء [ReturnAction](../../returnaction/).

## انظر أيضًا

* تعداد [ReturnAction](../../returnaction/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IWarningInfo](../../iwarninginfo/)
* فئة [IWarningCallback](../)
* نطاق [Aspose::Slides::Warnings](../../)
* مكتبة [Aspose.Slides](../../../)