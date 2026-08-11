---
title: set_TrimFromStart()
second_title: مرجع API Aspose.Slides للغة C++
description: بدء القطع [ms]
type: docs
weight: 222
url: /ar/aspose.slides/ivideoframe/set_trimfromstart/
---
## IVideoFrame::set_TrimFromStart(float) طريقة

بدء القطع [ms]

```cpp
virtual void Aspose::Slides::IVideoFrame::set_TrimFromStart(float value)=0
```

## ملاحظات

مثال: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//تحديد وقت بدء القطع 1 ثانية
videoFrame->set_TrimFromStart(1000.0f);

//تحديد وقت انتهاء القطع 2 ثانية
videoFrame->set_TrimFromEnd(2000.0f);
```

## انظر أيضاً

* فئة [IVideoFrame](../)
* فضاء الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)