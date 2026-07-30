---
title: set_TrimFromStart()
second_title: Riferimento API di Aspose.Slides per C++
description: Ritaglia inizio [ms]
type: docs
weight: 222
url: /it/aspose.slides/videoframe/set_trimfromstart/
---
## VideoFrame::set_TrimFromStart(float) metodo

Ritaglia inizio [ms]

```cpp
void Aspose::Slides::VideoFrame::set_TrimFromStart(float value) override
```

## Osservazioni

Esempio: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//imposta il tempo di inizio del ritaglio a 1sec
videoFrame->set_TrimFromStart(1000.0f);

//imposta il tempo di fine del ritaglio a 2sec
videoFrame->set_TrimFromEnd(2000.0f);
```

## Vedi anche

* Classe [VideoFrame](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)