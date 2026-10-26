---
title: get_TrimFromStart()
second_title: Aspose.Slides pro C++ referenci API
description: Začátek ořezu [ms]
type: docs
weight: 209
url: /cs/aspose.slides/ivideoframe/get_trimfromstart/
---
## IVideoFrame::get_TrimFromStart() metoda


Začátek ořezu [ms]

```cpp
virtual float Aspose::Slides::IVideoFrame::get_TrimFromStart()=0
```

## Poznámky


Příklad: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//nastavit čas ořezu od začátku 1 sek
videoFrame->set_TrimFromStart(1000.0f);

//nastavit čas ořezu od konce 2 sek
videoFrame->set_TrimFromEnd(2000.0f);
```

## Viz také

* Třída [IVideoFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)