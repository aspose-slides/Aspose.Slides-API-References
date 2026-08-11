---
title: GetPresentationInfo()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ كائن PresentationInfo جديد من الملف ويربط العرض التقديمي به.
type: docs
weight: 27
url: /ar/aspose.slides/presentationfactory/getpresentationinfo/
---
## PresentationFactory::GetPresentationInfo(System::String) طريقة

ينشئ كائن [PresentationInfo](../../presentationinfo/) جديد من ملف ويربط العرض التقديمي به.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::String file) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | ملف [Presentation](../../presentation/). |

### قيمة الإرجاع

معلومات [Presentation](../../presentation/) المرتبطة بالعرض التقديمي.

## PresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) طريقة

ينشئ كائن [PresentationInfo](../../presentationinfo/) جديد من الدفق ويربط العرض التقديمي به. يحصل على معلومات حول العرض التقديمي في الدفق المحدد.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | دفق [Presentation](../../presentation/). |

### قيمة الإرجاع

معلومات [Presentation](../../presentation/) المرتبطة بالعرض التقديمي.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IPresentationInfo](../../ipresentationinfo/)
* فئة [String](../../../system/string/)
* فئة [PresentationFactory](../)
* فئة [Stream](../../../system.io/stream/)
* النطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)