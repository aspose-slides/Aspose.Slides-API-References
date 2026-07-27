---
title: set_TrimFromStart()
second_title: Referência da API Aspose.Slides para C++
description: Início do corte [ms]
type: docs
weight: 222
url: /pt/aspose.slides/ivideoframe/set_trimfromstart/
---
## IVideoFrame::set_TrimFromStart(float) método


Início do corte [ms]

```cpp
virtual void Aspose::Slides::IVideoFrame::set_TrimFromStart(float value)=0
```

## Observações


Exemplo: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//definir tempo de início do corte 1 seg
videoFrame->set_TrimFromStart(1000.0f);

//definir tempo de fim do corte 2 seg
videoFrame->set_TrimFromEnd(2000.0f);
```

## Ver também

* Classe [IVideoFrame](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)