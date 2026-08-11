---
title: get_CaptionTracks()
second_title: Aspose.Slides للغة C++ مرجع API
description: يحصل على مجموعة الترجمات المغلقة المرتبطة بإطار الصوت. هذه الخاصية للقراءة فقط وتعيد ICaptionsCollection يحتوي على جميع مسارات الترجمات.
type: docs
weight: 456
url: /ar/aspose.slides/iaudioframe/get_captiontracks/
---
## IAudioFrame::get_CaptionTracks() طريقة


يحصل على مجموعة الترجمات المغلقة المرتبطة بإطار الصوت. هذه الخاصية للقراءة فقط وتعيد [ICaptionsCollection](../../icaptionscollection/) يحتوي على جميع مسارات الترجمات.

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IAudioFrame::get_CaptionTracks()=0
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
        // احفظ البيانات الثنائية لمسار الترجمات كملف .vtt
        for (auto&& captionTrack : audioFrame->get_CaptionTracks())
        {
            System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
        }
    }
}
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [ICaptionsCollection](../../icaptionscollection/)
* فئة [IAudioFrame](../)
* فضاء الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)