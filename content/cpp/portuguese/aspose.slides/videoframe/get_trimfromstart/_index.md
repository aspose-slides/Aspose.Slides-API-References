---
title: get_TrimFromStart()
second_title: Aspose.Slides para C++ Referência da API
description: Início do recorte [ms]
type: docs
weight: 209
url: /pt/aspose.slides/videoframe/get_trimfromstart/
---
## VideoFrame::get_TrimFromStart() método


Início do recorte [ms]

```cpp
float Aspose::Slides::VideoFrame::get_TrimFromStart() override
```

## Observações


Exemplo: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//definir tempo de início de corte 1 seg
videoFrame->set_TrimFromStart(1000.0f);

//definir tempo de fim de corte 2 seg
videoFrame->set_TrimFromEnd(2000.0f);
```

## Veja também

* Classe [VideoFrame](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)