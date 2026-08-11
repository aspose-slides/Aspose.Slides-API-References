---
title: RegisterPrefix()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يسجل السليل WebRequest للـ URI المحدد.
type: docs
weight: 92
url: /ar/system.net/webrequest/registerprefix/
---
## WebRequest::RegisterPrefix(String, System::SharedPtr\<IWebRequestCreate\>) طريقة

يسجل السليل [WebRequest](../) للـ URI المحدد.

```cpp
static bool System::Net::WebRequest::RegisterPrefix(String prefix, System::SharedPtr<IWebRequestCreate> creator)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | الـ URI أو بادئة الـ URI. |
| creator | [System::SharedPtr](../../../system/sharedptr/)\<[IWebRequestCreate](../../iwebrequestcreate/)\> | ينشئ مثيلات جديدة من الفئة [WebRequest](../). |

### قيمة الإرجاع

True عندما يتم تسجيل السليل [WebRequest](../) بنجاح للـ URI المحدد، وإلا false.

## انظر أيضا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [IWebRequestCreate](../../iwebrequestcreate/)
* فئة [WebRequest](../)
* مساحة أسماء [System::Net](../../)
* مكتبة [Aspose.Slides](../../../)