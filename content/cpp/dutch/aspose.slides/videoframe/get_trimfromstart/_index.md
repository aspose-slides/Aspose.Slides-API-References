---
title: get_TrimFromStart()
second_title: Aspose.Slides voor C++ API-referentie
description: Start trimmen [ms]
type: docs
weight: 209
url: /nl/aspose.slides/videoframe/get_trimfromstart/
---
## VideoFrame::get_TrimFromStart() methode


Start trimmen [ms]

```cpp
float Aspose::Slides::VideoFrame::get_TrimFromStart() override
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
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)