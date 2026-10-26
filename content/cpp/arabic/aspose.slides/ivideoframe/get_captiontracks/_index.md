---
title: get_CaptionTracks()
second_title: مرجع API Aspose.Slides للـ C++
description: يحصل على مجموعة التسميات التوضيحية المغلقة المرتبطة بإطار الصوت. هذه الخاصية للقراءة فقط وتعيد ICaptionsCollection يحتوي على جميع مسارات التسميات التوضيحية.
type: docs
weight: 261
url: /ar/aspose.slides/ivideoframe/get_captiontracks/
---
## IVideoFrame::get_CaptionTracks() طريقة

يحصل على مجموعة التسميات التوضيحية المغلقة المرتبطة بإطار الصوت. هذه الخاصية للقراءة فقط وتعيد [ICaptionsCollection](../../icaptionscollection/) يحتوي على جميع مسارات التسميات التوضيحية.

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IVideoFrame::get_CaptionTracks()=0
```

## ملاحظات


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
        // يستخرج البيانات الثنائية للتسميات التوضيحية ويحفظها في الملف
        System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
    }
}
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ICaptionsCollection](../../icaptionscollection/)
* فئة [IVideoFrame](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)