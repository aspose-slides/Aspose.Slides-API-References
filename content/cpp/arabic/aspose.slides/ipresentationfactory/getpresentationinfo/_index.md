---
title: GetPresentationInfo()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحصل على معلومات حول العرض التقديمي في الملف المحدد.
type: docs
weight: 14
url: /ar/aspose.slides/ipresentationfactory/getpresentationinfo/
---
## IPresentationFactory::GetPresentationInfo(System::String) طريقة

يحصل على معلومات حول العرض التقديمي في الملف المحدد.

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::String file)=0
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) ملف. |

### قيمة الإرجاع

[Presentation](../../presentation/) معلومات

## IPresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) طريقة

يحصل على معلومات حول العرض التقديمي في الدفق المحدد.

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream)=0
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) تدفق. |

### قيمة الإرجاع

[Presentation](../../presentation/) معلومات.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IPresentationInfo](../../ipresentationinfo/)
* فئة [String](../../../system/string/)
* فئة [IPresentationFactory](../)
* فئة [Stream](../../../system.io/stream/)
* نطاق [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)