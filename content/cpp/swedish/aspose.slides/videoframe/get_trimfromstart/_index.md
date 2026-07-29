---
title: get_TrimFromStart()
second_title: Aspose.Slides för C++ API-referens
description: Beskärningsstart [ms]
type: docs
weight: 209
url: /sv/aspose.slides/videoframe/get_trimfromstart/
---
## VideoFrame::get_TrimFromStart() metod


Beskärningsstart [ms]

```cpp
float Aspose::Slides::VideoFrame::get_TrimFromStart() override
```

## Anmärkningar


Exempel: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//set triming start time 1sec
videoFrame->set_TrimFromStart(1000.0f);

//set triming end time 2sec
videoFrame->set_TrimFromEnd(2000.0f);
```

## Se även

* Klass [VideoFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)