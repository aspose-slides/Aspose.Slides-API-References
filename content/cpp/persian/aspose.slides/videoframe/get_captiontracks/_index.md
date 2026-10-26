---
title: get_CaptionTracks()
second_title: مرجع API Aspose.Slides برای C++
description: مجموعهٔ زیرنویس‌های بسته شده مرتبط با قاب ویدئو را دریافت می‌کند. این ویژگی فقط-خواندنی است و یک ICaptionsCollection که شامل تمام مسیرهای زیرنویس است، برمی‌گرداند.
type: docs
weight: 261
url: /fa/aspose.slides/videoframe/get_captiontracks/
---
## VideoFrame::get_CaptionTracks() متد

مجموعه زیرنویس‌های بسته شده مرتبط با قاب ویدئو را دریافت می‌کند. این ویژگی فقط-خواندنی است و یک [ICaptionsCollection](../../icaptionscollection/) که شامل تمام مسیرهای زیرنویس می‌باشد، برمی‌گرداند.

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::VideoFrame::get_CaptionTracks() override
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
        // داده‌های باینری زیرنویس‌ها را استخراج می‌کند و آنها را در فایل ذخیره می‌نماید
        System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
    }
}
```

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ICaptionsCollection](../../icaptionscollection/)
* کلاس [VideoFrame](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)