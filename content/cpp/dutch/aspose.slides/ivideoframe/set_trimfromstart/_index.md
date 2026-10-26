---
title: set_TrimFromStart()
second_title: Aspose.Slides voor C++ API-referentie
description: Begin trimmen [ms]
type: docs
weight: 222
url: /nl/aspose.slides/ivideoframe/set_trimfromstart/
---
## IVideoFrame::set_TrimFromStart(float) method

Begin trimmen [ms]

```cpp
virtual void Aspose::Slides::IVideoFrame::set_TrimFromStart(float value)=0
```

## Opmerkingen


Voorbeeld: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//stel trimmen starttijd in op 1 sec
videoFrame->set_TrimFromStart(1000.0f);

//stel trimmen eindtijd in op 2 sec
videoFrame->set_TrimFromEnd(2000.0f);
```

## Zie ook

* Klasse [IVideoFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)