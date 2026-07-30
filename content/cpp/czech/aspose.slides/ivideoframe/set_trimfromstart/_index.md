---
title: set_TrimFromStart()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Odříznutí od začátku [ms]
type: docs
weight: 222
url: /cs/aspose.slides/ivideoframe/set_trimfromstart/
---
## IVideoFrame::set_TrimFromStart(float) metoda


Odříznutí od začátku [ms]

```cpp
virtual void Aspose::Slides::IVideoFrame::set_TrimFromStart(float value)=0
```

## Poznámky


Příklad: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//nastavit počáteční čas ořezu na 1 s
videoFrame->set_TrimFromStart(1000.0f);

//nastavit koncový čas ořezu na 2 s
videoFrame->set_TrimFromEnd(2000.0f);
```

## Viz také

* Třída [IVideoFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)