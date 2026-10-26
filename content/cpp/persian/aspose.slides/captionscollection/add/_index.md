---
title: Add()
second_title: Aspose.Slides برای C++ مرجع API
description: کپشن‌های بسته WebVTT را به انتهای مجموعه اضافه می‌کند.
type: docs
weight: 27
url: /fa/aspose.slides/captionscollection/add/
---
## CaptionsCollection::Add(System::String, System::String) متد

کپشن‌های بسته WebVTT را به انتهای مجموعه اضافه می‌کند.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::String filePath) override
```

### پارامترها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | برچسب زیرنویس‌های بسته. |
| filePath | [System::String](../../../system/string/) | مسیر فایل WebVTT. |

### مقدار بازگشت

نمونهٔ اضافه‌شده [ICaptions](../../icaptions/).

## CaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) متد

زیرنویس‌های بسته WebVTT را از یک جریان به انتهای مجموعه اضافه می‌کند.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream) override
```

### پارامترها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | برچسب زیرنویس‌های بسته. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریان ورودی که شامل داده‌های با فرمت WebVTT است. |

### مقدار بازگشت

نمونهٔ اضافه‌شده [ICaptions](../../icaptions/).

## مشاهده کنید

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICaptions](../../icaptions/)
* Class [String](../../../system/string/)
* Class [CaptionsCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)