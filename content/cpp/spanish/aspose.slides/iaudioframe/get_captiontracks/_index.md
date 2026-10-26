---
title: get_CaptionTracks()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene la colección de subtítulos cerrados asociados al marco de audio. Esta propiedad es de solo lectura y devuelve una ICaptionsCollection que contiene todas las pistas de subtítulos.
type: docs
weight: 456
url: /es/aspose.slides/iaudioframe/get_captiontracks/
---
## IAudioFrame::get_CaptionTracks() método


Obtiene la colección de subtítulos cerrados asociados con el marco de audio. Esta propiedad es de solo lectura y devuelve un [ICaptionsCollection](../../icaptionscollection/) que contiene todas las pistas de subtítulos.

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IAudioFrame::get_CaptionTracks()=0
```

## Observaciones


Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"audio with captions.pptx");
for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    if (System::ObjectExt::Is<IAudioFrame>(shape))
    {
        System::SharedPtr<IAudioFrame> audioFrame = System::ExplicitCast<IAudioFrame>(shape);
        // Guardar los datos binarios de la pista de subtítulos como un archivo .vtt
        for (auto&& captionTrack : audioFrame->get_CaptionTracks())
        {
            System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
        }
    }
}
```

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICaptionsCollection](../../icaptionscollection/)
* Class [IAudioFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)