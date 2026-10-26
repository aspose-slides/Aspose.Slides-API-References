---
title: Add()
second_title: مرجع API Aspose.Slides برای C++
description: زیرنویس‌های بستهٔ WebVTT را به انتهای مجموعه اضافه می‌کند.
type: docs
weight: 27
url: /fa/aspose.slides/icaptionscollection/add/
---
## ICaptionsCollection::Add(System::String, System::String) متد

زیرنویس‌های بستهٔ WebVTT را به انتهای مجموعه اضافه می‌کند.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::String filePath)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | برچسب زیرنویس‌های بسته. |
| filePath | [System::String](../../../system/string/) | مسیر فایل WebVTT. |

### مقدار بازگشت

نمونهٔ اضافه‌شدهٔ [ICaptions](../../icaptions/).

## ICaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) متد

زیرنویس‌های بستهٔ WebVTT را از یک جریان به انتهای مجموعه اضافه می‌کند.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | برچسب زیرنویس‌های بسته. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریان ورودی حاوی داده‌های با قالب WebVTT. |

### مقدار بازگشت

نمونهٔ اضافه‌شدهٔ [ICaptions](../../icaptions/).

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [ICaptions](../../icaptions/)
* کلاس [String](../../../system/string/)
* کلاس [ICaptionsCollection](../)
* کلاس [Stream](../../../system.io/stream/)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)