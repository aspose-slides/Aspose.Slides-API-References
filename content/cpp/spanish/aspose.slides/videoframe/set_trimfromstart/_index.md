---
title: set_TrimFromStart()
second_title: Referencia de API de Aspose.Slides para C++
description: Inicio de recorte [ms]
type: docs
weight: 222
url: /es/aspose.slides/videoframe/set_trimfromstart/
---
## VideoFrame::set_TrimFromStart(float) método

Inicio de recorte [ms]

```cpp
void Aspose::Slides::VideoFrame::set_TrimFromStart(float value) override
```

## Observaciones

Ejemplo: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//establecer el inicio del recorte a 1 segundo
videoFrame->set_TrimFromStart(1000.0f);

//establecer el fin del recorte a 2 segundos
videoFrame->set_TrimFromEnd(2000.0f);
```

## Ver también

* Clase [VideoFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)