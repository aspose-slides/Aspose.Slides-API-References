---
title: GetPresentationInfo()
second_title: مرجع API Aspose.Slides برای C++
description: یک شیء PresentationInfo جدید را از فایل ایجاد می‌کند و ارائه را به آن متصل می‌سازد.
type: docs
weight: 27
url: /fa/aspose.slides/presentationfactory/getpresentationinfo/
---
## PresentationFactory::GetPresentationInfo(System::String) متد


یک شیء جدید [PresentationInfo](../../presentationinfo/) را از فایل ایجاد می‌کند و ارائه را به آن متصل می‌کند.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::String file) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) فایل. |

### مقدار بازگشتی

[Presentation](../../presentation/) اطلاعات به ارائه متصل شده است.

## PresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) متد


یک شیء جدید [PresentationInfo](../../presentationinfo/) را از جریان ایجاد می‌کند و ارائه را به آن متصل می‌کند. اطلاعات مربوط به ارائه در جریان مشخص شده را دریافت می‌کند.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) جریان. |

### مقدار بازگشتی

[Presentation](../../presentation/) اطلاعات به ارائه متصل شده است.

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IPresentationInfo](../../ipresentationinfo/)
* کلاس [String](../../../system/string/)
* کلاس [PresentationFactory](../)
* کلاس [Stream](../../../system.io/stream/)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)