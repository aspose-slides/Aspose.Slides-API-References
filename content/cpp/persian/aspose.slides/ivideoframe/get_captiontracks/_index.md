---
title: get_CaptionTracks()
second_title: مرجع API Aspose.Slides برای C++
description: مجموعهٔ زیرنویس‌های بسته مرتبط با فریم صوتی را دریافت می‌کند. این ویژگی فقط-خواندنی است و یک ICaptionsCollection شامل تمام مسیرهای زیرنویس را برمی‌گرداند.
type: docs
weight: 261
url: /fa/aspose.slides/ivideoframe/get_captiontracks/
---
## IVideoFrame::get_CaptionTracks() متد

مجموعه‌ی زیرنویس‌های بسته که با فریم صوتی مرتبط هستند را دریافت می‌کند. این ویژگی فقط-خواندنی است و یک [ICaptionsCollection](../../icaptionscollection/) حاوی تمام مسیرهای زیرنویس را برمی‌گرداند.

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IVideoFrame::get_CaptionTracks()=0
```

## توضیحات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"video with captions.pptx");

for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    System::SharedPtr<IVideoFrame> videoFrame = System::AsCast<IVideoFrame>(shape);
    if (videoFrame != nullptr)
    {
        continue;
    }

    for (auto&& captionTrack : videoFrame->get_CaptionTracks())
    {
        // استخراج داده‌های باینری زیرنویس‌ها و ذخیره آن‌ها در فایل
        System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
    }
}
```

## همچنین ببینید

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [ICaptionsCollection](../../icaptionscollection/)
* کلاس [IVideoFrame](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)