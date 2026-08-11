---
title: get_CaptionTracks()
second_title: مرجع API Aspose.Slides برای C++
description: مجموعه‌ای از زیرنویس‌های بسته مربوط به فریم صوتی را دریافت می‌کند. این ویژگی فقط-خواندنی است و یک ICaptionsCollection شامل تمام مسیرهای زیرنویس را برمی‌گرداند.
type: docs
weight: 456
url: /fa/aspose.slides/iaudioframe/get_captiontracks/
---
## IAudioFrame::get_CaptionTracks() متد

مجموعه‌ای از زیرنویس‌های بسته مرتبط با فریم صوتی را دریافت می‌کند. این ویژگی فقط-خواندنی است و یک [ICaptionsCollection](../../icaptionscollection/) حاوی تمام مسیرهای زیرنویس را برمی‌گرداند.

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IAudioFrame::get_CaptionTracks()=0
```

## توضیحات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"audio with captions.pptx");
for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    if (System::ObjectExt::Is<IAudioFrame>(shape))
    {
        System::SharedPtr<IAudioFrame> audioFrame = System::ExplicitCast<IAudioFrame>(shape);
        // داده‌های باینری مسیر زیرنویس را به‌عنوان یک فایل .vtt ذخیره کنید
        for (auto&& captionTrack : audioFrame->get_CaptionTracks())
        {
            System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
        }
    }
}
```

## همچنین ببینید

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ICaptionsCollection](../../icaptionscollection/)
* کلاس [IAudioFrame](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)