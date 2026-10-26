---
title: get_TrimFromStart()
second_title: مرجع API Aspose.Slides للغة C++
description: قص البداية [ms]
type: docs
weight: 209
url: /ar/aspose.slides/videoframe/get_trimfromstart/
---
## VideoFrame::get_TrimFromStart() طريقة

قص البداية [ms]

```cpp
float Aspose::Slides::VideoFrame::get_TrimFromStart() override
```

## ملاحظات

مثال: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//تعيين وقت بدء القطع 1 ثانية
videoFrame->set_TrimFromStart(1000.0f);

//تعيين وقت انتهاء القطع 2 ثانية
videoFrame->set_TrimFromEnd(2000.0f);
```

## انظر أيضًا

* فئة [VideoFrame](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)