---
title: get_TrimFromStart()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ตัดจุดเริ่มต้น [ms]
type: docs
weight: 209
url: /th/aspose.slides/videoframe/get_trimfromstart/
---
## VideoFrame::get_TrimFromStart() เมธอด


ตัดจุดเริ่มต้น [ms]

```cpp
float Aspose::Slides::VideoFrame::get_TrimFromStart() override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//ตั้งค่าการตัดเริ่มต้น 1 วินาที
videoFrame->set_TrimFromStart(1000.0f);

//ตั้งค่าการตัดสิ้นสุด 2 วินาที
videoFrame->set_TrimFromEnd(2000.0f);
```

## ดูเพิ่มเติม

* คลาส [VideoFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)