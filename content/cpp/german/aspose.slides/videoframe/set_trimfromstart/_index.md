---
title: set_TrimFromStart()
second_title: Aspose.Slides für C++ API-Referenz
description: Start abschneiden [ms]
type: docs
weight: 222
url: /de/aspose.slides/videoframe/set_trimfromstart/
---
## VideoFrame::set_TrimFromStart(float) Methode


Trim-Start [ms]

```cpp
void Aspose::Slides::VideoFrame::set_TrimFromStart(float value) override
```

## Hinweise


Beispiel: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//Trim-Startzeit auf 1 Sekunde setzen
videoFrame->set_TrimFromStart(1000.0f);

//Trim-Endzeit auf 2 Sekunden setzen
videoFrame->set_TrimFromEnd(2000.0f);
```

## Siehe auch

* Klasse [VideoFrame](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)