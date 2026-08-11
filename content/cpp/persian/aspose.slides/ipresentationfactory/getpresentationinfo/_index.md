---
title: GetPresentationInfo()
second_title: Aspose.Slides برای C++ مرجع API
description: اطلاعات ارائه در فایل مشخص شده را دریافت می‌کند.
type: docs
weight: 14
url: /fa/aspose.slides/ipresentationfactory/getpresentationinfo/
---
## IPresentationFactory::GetPresentationInfo(System::String) متد


اطلاعات ارائه در فایل مشخص شده را دریافت می‌کند.

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::String file)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) فایل. |

### مقدار بازگشتی

[Presentation](../../presentation/) اطلاعات

## IPresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) متد


اطلاعات ارائه در جریان مشخص شده را دریافت می‌کند.

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) جریان. |

### مقدار بازگشتی

[Presentation](../../presentation/) اطلاعات.

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IPresentationInfo](../../ipresentationinfo/)
* کلاس [String](../../../system/string/)
* کلاس [IPresentationFactory](../)
* کلاس [Stream](../../../system.io/stream/)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)