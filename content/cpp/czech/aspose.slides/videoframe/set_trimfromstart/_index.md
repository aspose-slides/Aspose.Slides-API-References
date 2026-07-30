---
title: set_TrimFromStart()
second_title: Aspose.Slides pro C++ – reference API
description: Začátek oříznutí [ms]
type: docs
weight: 222
url: /cs/aspose.slides/videoframe/set_trimfromstart/
---
## VideoFrame::set_TrimFromStart(float) metoda


Začátek oříznutí [ms]

```cpp
void Aspose::Slides::VideoFrame::set_TrimFromStart(float value) override
```

## Poznámky


Příklad:
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//nastavte čas oříznutí na začátku 1 s
videoFrame->set_TrimFromStart(1000.0f);

//nastavte čas oříznutí na konci 2 s
videoFrame->set_TrimFromEnd(2000.0f);
```

## Viz také

* Třída [VideoFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)