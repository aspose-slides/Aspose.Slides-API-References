---
title: set_TrimFromStart()
second_title: Riferimento API di Aspose.Slides per C++
description: Inizio del ritaglio [ms]
type: docs
weight: 222
url: /it/aspose.slides/ivideoframe/set_trimfromstart/
---
## IVideoFrame::set_TrimFromStart(float) metodo


Inizio del ritaglio [ms]

```cpp
virtual void Aspose::Slides::IVideoFrame::set_TrimFromStart(float value)=0
```

## Osservazioni


Esempio: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//imposta il tempo di inizio del ritaglio 1sec
videoFrame->set_TrimFromStart(1000.0f);

//imposta il tempo di fine del ritaglio 2sec
videoFrame->set_TrimFromEnd(2000.0f);
```

## Vedi anche

* Classe [IVideoFrame](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)