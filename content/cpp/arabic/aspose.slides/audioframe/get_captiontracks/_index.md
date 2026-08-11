---
title: get_CaptionTracks()
second_title: مرجع API Aspose.Slides للـ C++
description: يحصل على مجموعة الشروح المغلقة المرتبطة بإطار الصوت. هذه الخاصية للقراءة فقط وتعيد ICaptionsCollection يحتوي على جميع مسارات الشرح.
type: docs
weight: 456
url: /ar/aspose.slides/audioframe/get_captiontracks/
---
## AudioFrame::get_CaptionTracks() طريقة

يحصل على مجموعة الشروح المغلقة المرتبطة بإطار الصوت. هذه الخاصية للقراءة فقط وتعيد [ICaptionsCollection](../../icaptionscollection/) يحتوي على جميع مسارات الشروح.

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::AudioFrame::get_CaptionTracks() override
```

## ملاحظات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"audio with captions.pptx");
for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    if (System::ObjectExt::Is<IAudioFrame>(shape))
    {
        System::SharedPtr<IAudioFrame> audioFrame = System::ExplicitCast<IAudioFrame>(shape);
        // احفظ البيانات الثنائية لمسار الشرح كملف .vtt
        for (auto&& captionTrack : audioFrame->get_CaptionTracks())
        {
            System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
        }
    }
}
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ICaptionsCollection](../../icaptionscollection/)
* فئة [AudioFrame](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)