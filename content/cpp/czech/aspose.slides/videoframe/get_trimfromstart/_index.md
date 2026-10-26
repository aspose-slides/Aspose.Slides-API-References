---
title: get_TrimFromStart()
second_title: Aspose.Slides pro C++ API Reference
description: Zkrátit od začátku [ms]
type: docs
weight: 209
url: /cs/aspose.slides/videoframe/get_trimfromstart/
---
## VideoFrame::get_TrimFromStart() method

Zkrátit od začátku [ms]

```cpp
float Aspose::Slides::VideoFrame::get_TrimFromStart() override
```

## Poznámky

Příklad:
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//nastavit čas oříznutí od začátku 1 s
videoFrame->set_TrimFromStart(1000.0f);

//nastavit čas oříznutí od konce 2 s
videoFrame->set_TrimFromEnd(2000.0f);
```

## Viz také

* Třída [VideoFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)