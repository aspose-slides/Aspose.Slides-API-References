---
title: get_TrimFromStart()
second_title: Aspose.Slides för C++ API-referens
description: Trimningsstart [ms]
type: docs
weight: 209
url: /sv/aspose.slides/ivideoframe/get_trimfromstart/
---
## IVideoFrame::get_TrimFromStart() metod


Trim start [ms]

```cpp
virtual float Aspose::Slides::IVideoFrame::get_TrimFromStart()=0
```

## Anmärkningar


Exempel: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//sätt trimningsstarttid 1 sek
videoFrame->set_TrimFromStart(1000.0f);

//sätt trimningssluttid 2 sek
videoFrame->set_TrimFromEnd(2000.0f);
```

## Se även

* Klass [IVideoFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)