---
title: set_TrimFromStart()
second_title: Aspose.Slides voor C++ API-referentie
description: Start trimmen [ms]
type: docs
weight: 222
url: /nl/aspose.slides/videoframe/set_trimfromstart/
---
## VideoFrame::set_TrimFromStart(float) methode

Begin trimmen [ms]

```cpp
void Aspose::Slides::VideoFrame::set_TrimFromStart(float value) override
```

## Opmerkingen

Voorbeeld: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//stel trim starttijd in 1sec
videoFrame->set_TrimFromStart(1000.0f);

//stel trim eindtijd in 2sec
videoFrame->set_TrimFromEnd(2000.0f);
```

## Zie ook

* Klasse [VideoFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)