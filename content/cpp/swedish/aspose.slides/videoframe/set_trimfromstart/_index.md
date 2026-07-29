---
title: set_TrimFromStart()
second_title: Aspose.Slides för C++ API-referens
description: Trimma start [ms]
type: docs
weight: 222
url: /sv/aspose.slides/videoframe/set_trimfromstart/
---
## VideoFrame::set_TrimFromStart(float) metod


Trimma start [ms]

```cpp
void Aspose::Slides::VideoFrame::set_TrimFromStart(float value) override
```

## Anmärkningar


Exempel:
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//sätt trimning starttid 1 sek
videoFrame->set_TrimFromStart(1000.0f);

//sätt trimning sluttid 2 sek
videoFrame->set_TrimFromEnd(2000.0f);
```

## Se även

* Klass [VideoFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)