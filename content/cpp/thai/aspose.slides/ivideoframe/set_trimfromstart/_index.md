---
title: set_TrimFromStart()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตัดส่วนเริ่มต้น [ms]
type: docs
weight: 222
url: /th/aspose.slides/ivideoframe/set_trimfromstart/
---
## IVideoFrame::set_TrimFromStart(float) เมธอด

Trim start [ms]

```cpp
virtual void Aspose::Slides::IVideoFrame::set_TrimFromStart(float value)=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//ตั้งเวลาเริ่มต้น 1 วินาที
videoFrame->set_TrimFromStart(1000.0f);

//ตั้งเวลาสิ้นสุด 2 วินาที
videoFrame->set_TrimFromEnd(2000.0f);
```

## ดูเพิ่มเติม

* คลาส [IVideoFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)