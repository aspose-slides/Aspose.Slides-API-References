---
title: set_TrimFromStart()
second_title: مرجع API Aspose.Slides للـ C++
description: بدء التقليم [ms]
type: docs
weight: 222
url: /ar/aspose.slides/videoframe/set_trimfromstart/
---
## VideoFrame::set_TrimFromStart(float) طريقة

بدء التقليم [ms]

```cpp
void Aspose::Slides::VideoFrame::set_TrimFromStart(float value) override
```

## ملاحظات

مثال:
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//ضبط بدء التقليم 1 ثانية
videoFrame->set_TrimFromStart(1000.0f);

//ضبط انتهاء التقليم 2 ثانية
videoFrame->set_TrimFromEnd(2000.0f);
```

## انظر أيضًا

* الفئة [VideoFrame](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)