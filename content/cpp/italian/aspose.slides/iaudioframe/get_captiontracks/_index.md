---
title: get_CaptionTracks()
second_title: Aspose.Slides per C++ Riferimento API
description: Restituisce la raccolta di sottotitoli chiusi associati al fotogramma audio. Questa proprietà è di sola lettura e restituisce un ICaptionsCollection contenente tutte le tracce di sottotitoli.
type: docs
weight: 456
url: /it/aspose.slides/iaudioframe/get_captiontracks/
---
## IAudioFrame::get_CaptionTracks() metodo

Restituisce la raccolta di sottotitoli chiusi associati al fotogramma audio. Questa proprietà è di sola lettura e restituisce un [ICaptionsCollection](../../icaptionscollection/) contenente tutte le tracce di sottotitoli.

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IAudioFrame::get_CaptionTracks()=0
```

## Osservazioni

Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"audio with captions.pptx");
for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    if (System::ObjectExt::Is<IAudioFrame>(shape))
    {
        System::SharedPtr<IAudioFrame> audioFrame = System::ExplicitCast<IAudioFrame>(shape);
        // Salva i dati binari della traccia di sottotitoli come file .vtt
        for (auto&& captionTrack : audioFrame->get_CaptionTracks())
        {
            System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
        }
    }
}
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ICaptionsCollection](../../icaptionscollection/)
* Classe [IAudioFrame](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)