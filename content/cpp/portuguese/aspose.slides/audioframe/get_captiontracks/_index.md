---
title: get_CaptionTracks()
second_title: Aspose.Slides para C++ Referência da API
description: Obtém a coleção de legendas fechadas associadas ao quadro de áudio. Esta propriedade é somente leitura e retorna um ICaptionsCollection contendo todas as faixas de legenda.
type: docs
weight: 456
url: /pt/aspose.slides/audioframe/get_captiontracks/
---
## AudioFrame::get_CaptionTracks() método

Obtém a coleção de legendas fechadas associadas ao quadro de áudio. Esta propriedade é somente leitura e retorna um [ICaptionsCollection](../../icaptionscollection/) contendo todas as faixas de legenda.

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::AudioFrame::get_CaptionTracks() override
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
        // Salve os dados binários da faixa de legendas como um arquivo .vtt
        for (auto&& captionTrack : audioFrame->get_CaptionTracks())
        {
            System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
        }
    }
}
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ICaptionsCollection](../../icaptionscollection/)
* Classe [AudioFrame](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)