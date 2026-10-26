---
title: get_CaptionTracks()
second_title: Referência da API Aspose.Slides para C++
description: Obtém a coleção de legendas fechadas associadas ao quadro de áudio. Esta propriedade é somente leitura e retorna um ICaptionsCollection contendo todas as pistas de legendas.
type: docs
weight: 456
url: /pt/aspose.slides/iaudioframe/get_captiontracks/
---
## IAudioFrame::get_CaptionTracks() método

Obtém a coleção de legendas fechadas associadas ao quadro de áudio. Esta propriedade é somente leitura e retorna um [ICaptionsCollection](../../icaptionscollection/) contendo todas as pistas de legendas.

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IAudioFrame::get_CaptionTracks()=0
```

## Observações

Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"audio with captions.pptx");
for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    if (System::ObjectExt::Is<IAudioFrame>(shape))
    {
        System::SharedPtr<IAudioFrame> audioFrame = System::ExplicitCast<IAudioFrame>(shape);
        // Salve os dados binários da faixa de legenda como um arquivo .vtt
        for (auto&& captionTrack : audioFrame->get_CaptionTracks())
        {
            System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
        }
    }
}
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICaptionsCollection](../../icaptionscollection/)
* Class [IAudioFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)