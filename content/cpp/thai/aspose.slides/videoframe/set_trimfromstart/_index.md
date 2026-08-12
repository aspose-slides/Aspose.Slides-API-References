---
title: set_TrimFromStart()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ตัดเริ่มต้น [ms]
type: docs
weight: 222
url: /th/aspose.slides/videoframe/set_trimfromstart/
---
## VideoFrame::set_TrimFromStart(float) เมธอด


ตัดเริ่มต้น [ms]

```cpp
void Aspose::Slides::VideoFrame::set_TrimFromStart(float value) override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//กำหนดเวลาเริ่มการตัด 1 วินาที
videoFrame->set_TrimFromStart(1000.0f);

//กำหนดเวลาเสร็จการตัด 2 วินาที
videoFrame->set_TrimFromEnd(2000.0f);
```

## ดูเพิ่มเติม

* คลาส [VideoFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)