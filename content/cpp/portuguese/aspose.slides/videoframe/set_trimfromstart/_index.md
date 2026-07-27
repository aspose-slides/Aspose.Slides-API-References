---
title: set_TrimFromStart()
second_title: Referência da API Aspose.Slides para C++
description: Início de recorte [ms]
type: docs
weight: 222
url: /pt/aspose.slides/videoframe/set_trimfromstart/
---
## VideoFrame::set_TrimFromStart(float) método


Início de recorte [ms]

```cpp
void Aspose::Slides::VideoFrame::set_TrimFromStart(float value) override
```

## Observações


Exemplo: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//definir tempo de início do recorte 1seg
videoFrame->set_TrimFromStart(1000.0f);

//definir tempo de fim do recorte 2seg
videoFrame->set_TrimFromEnd(2000.0f);
```

## Ver também

* Classe [VideoFrame](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)