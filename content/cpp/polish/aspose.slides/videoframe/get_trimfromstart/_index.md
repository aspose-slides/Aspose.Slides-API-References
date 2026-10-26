---
title: get_TrimFromStart()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Przycięcie od początku [ms]
type: docs
weight: 209
url: /pl/aspose.slides/videoframe/get_trimfromstart/
---
## VideoFrame::get_TrimFromStart() metoda


Przycięcie od początku [ms]

```cpp
float Aspose::Slides::VideoFrame::get_TrimFromStart() override
```

## Uwagi


Przykład: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//ustaw początkowy czas przycinania na 1 sek
videoFrame->set_TrimFromStart(1000.0f);

//ustaw końcowy czas przycinania na 2 sek
videoFrame->set_TrimFromEnd(2000.0f);
```

## Zobacz także

* Klasa [VideoFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)