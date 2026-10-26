---
title: GetEntity()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يقوم بربط URI بكائن يحتوي على المورد الفعلي.
type: docs
weight: 14
url: /ar/aspose.slides.import/iexternalresourceresolver/getentity/
---
## IExternalResourceResolver::GetEntity(System::String) طريقة


يُحوِّل URI إلى كائن يحتوي على المورد الفعلي.

```cpp
virtual System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::IExternalResourceResolver::GetEntity(System::String absoluteUri)=0
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | URI كامل إلى الكائن. |

### قيمة الإرجاع

كائن [System::IO::Stream](../../../system.io/stream/) أو null إذا تعذّر بث المورد.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [Stream](../../../system.io/stream/)
* الفئة [String](../../../system/string/)
* الفئة [IExternalResourceResolver](../)
* مساحة الاسم [Aspose::Slides::Import](../../)
* المكتبة [Aspose.Slides](../../../)