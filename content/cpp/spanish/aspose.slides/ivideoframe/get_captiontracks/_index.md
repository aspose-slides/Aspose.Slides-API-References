---
title: get_CaptionTracks()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene la colección de subtítulos cerrados asociados al cuadro de audio. Esta propiedad es de solo lectura y devuelve una ICaptionsCollection que contiene todas las pistas de subtítulos.
type: docs
weight: 261
url: /es/aspose.slides/ivideoframe/get_captiontracks/
---
## IVideoFrame::get_CaptionTracks() método

Obtiene la colección de subtítulos cerrados asociados al cuadro de audio. Esta propiedad es de solo lectura y devuelve un [ICaptionsCollection](../../icaptionscollection/) que contiene todas las pistas de subtítulos.

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IVideoFrame::get_CaptionTracks()=0
```

## Observaciones

Ejemplo:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"video with captions.pptx");

for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    System::SharedPtr<IVideoFrame> videoFrame = System::AsCast<IVideoFrame>(shape);
    if (videoFrame != nullptr)
    {
        continue;
    }

    for (auto&& captionTrack : videoFrame->get_CaptionTracks())
    {
        // Extrae los datos binarios de los subtítulos y los guarda en el archivo
        System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
    }
}
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ICaptionsCollection](../../icaptionscollection/)
* Clase [IVideoFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)