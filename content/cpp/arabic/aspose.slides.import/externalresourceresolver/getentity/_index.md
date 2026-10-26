---
title: GetEntity()
second_title: مرجع API ل Aspose.Slides للغة C++
description: يقوم بربط URI بكائن يحتوي على المورد الفعلي.
type: docs
weight: 14
url: /ar/aspose.slides.import/externalresourceresolver/getentity/
---
## ExternalResourceResolver::GetEntity(System::String) طريقة

يقوم بربط URI بكائن يحتوي على المورد الفعلي.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::ExternalResourceResolver::GetEntity(System::String absoluteUri) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | URI مطلق إلى الكائن. |

### قيمة الإرجاع

كائن [System::IO::Stream](../../../system.io/stream/) أو null إذا تعذر بث المورد.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [Stream](../../../system.io/stream/)
* فئة [String](../../../system/string/)
* فئة [ExternalResourceResolver](../)
* نطاق [Aspose::Slides::Import](../../)
* مكتبة [Aspose.Slides](../../../)