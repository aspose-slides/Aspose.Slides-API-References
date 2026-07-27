---
title: get_TrimFromStart()
second_title: Referencia de API de Aspose.Slides para C++
description: Recorte inicial [ms]
type: docs
weight: 209
url: /es/aspose.slides/videoframe/get_trimfromstart/
---
## VideoFrame::get_TrimFromStart() método


Recorte inicial [ms]

```cpp
float Aspose::Slides::VideoFrame::get_TrimFromStart() override
```

## Observaciones


Ejemplo: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//establecer tiempo de inicio de recorte 1seg
videoFrame->set_TrimFromStart(1000.0f);

//establecer tiempo de fin de recorte 2seg
videoFrame->set_TrimFromEnd(2000.0f);
```

## Ver también

* Clase [VideoFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)