---
title: get_CaptionTracks()
second_title: مرجع API Aspose.Slides لـ C++
description: يقوم باسترجاع مجموعة العناوين التوضيحية المغلقة المرتبطة بإطار الفيديو. هذه الخاصية للقراءة فقط وتعيد ICaptionsCollection يحتوي على جميع مسارات التسمية التوضيحية.
type: docs
weight: 261
url: /ar/aspose.slides/videoframe/get_captiontracks/
---
## VideoFrame::get_CaptionTracks() الطريقة

تسترجع مجموعة العناوين التوضيحية المغلقة المرتبطة بإطار الفيديو. هذه الخاصية للقراءة فقط وتعيد [ICaptionsCollection](../../icaptionscollection/) يحتوي على جميع مسارات التسمية التوضيحية.

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::VideoFrame::get_CaptionTracks() override
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [ICaptionsCollection](../../icaptionscollection/)
* فئة [VideoFrame](../)
* مساحة الاسم [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)