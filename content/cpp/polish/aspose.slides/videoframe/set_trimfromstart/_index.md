---
title: set_TrimFromStart()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Przycięcie początkowe [ms]
type: docs
weight: 222
url: /pl/aspose.slides/videoframe/set_trimfromstart/
---
## VideoFrame::set_TrimFromStart(float) metoda


Początek przycięcia [ms]

```cpp
void Aspose::Slides::VideoFrame::set_TrimFromStart(float value) override
```

## Uwagi


Przykład: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//ustaw początkowy czas przycinania 1 sek
videoFrame->set_TrimFromStart(1000.0f);

//ustaw końcowy czas przycinania 2 sek
videoFrame->set_TrimFromEnd(2000.0f);
```

## Zobacz także

* Klasa [VideoFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)