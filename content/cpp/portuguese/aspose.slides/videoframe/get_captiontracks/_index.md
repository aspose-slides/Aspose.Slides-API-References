---
title: get_CaptionTracks()
second_title: Referência da API Aspose.Slides para C++
description: Obtém a coleção de legendas fechadas associadas ao quadro de vídeo. Esta propriedade é somente leitura e retorna um ICaptionsCollection contendo todas as faixas de legenda.
type: docs
weight: 261
url: /pt/aspose.slides/videoframe/get_captiontracks/
---
## VideoFrame::get_CaptionTracks() método


Obtém a coleção de legendas fechadas associadas ao quadro de vídeo. Esta propriedade é somente leitura e retorna um [ICaptionsCollection](../../icaptionscollection/) contendo todas as faixas de legenda.

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::VideoFrame::get_CaptionTracks() override
```

## Observações


Exemplo: 
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
        // Extrai os dados binários das legendas e os salva no arquivo
        System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
    }
}
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ICaptionsCollection](../../icaptionscollection/)
* Classe [VideoFrame](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)