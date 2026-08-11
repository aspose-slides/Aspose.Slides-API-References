---
title: get_CaptionTracks()
second_title: مرجع API Aspose.Slides برای C++
description: دریافت مجموعه‌ای از زیرنویس‌های بسته مرتبط با قاب صدا. این ویژگی فقط-خواندنی است و یک ICaptionsCollection حاوی تمام مسیرهای زیرنویس را برمی‌گرداند.
type: docs
weight: 456
url: /fa/aspose.slides/audioframe/get_captiontracks/
---
## AudioFrame::get_CaptionTracks() متد

دریافت مجموعه‌ای از زیرنویس‌های بسته مرتبط با قاب صدا. این ویژگی فقط-خواندنی است و یک [ICaptionsCollection](../../icaptionscollection/) حاوی تمام مسیرهای زیرنویس را بر می‌گرداند.

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::AudioFrame::get_CaptionTracks() override
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
        // داده‌های باینری مسیر زیرنویس را به صورت فایل .vtt ذخیره کنید
        for (auto&& captionTrack : audioFrame->get_CaptionTracks())
        {
            System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
        }
    }
}
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [ICaptionsCollection](../../icaptionscollection/)
* کلاس [AudioFrame](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)