---
title: get_CaptionTracks()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene la collezione di sottotitoli chiusi associati al frame audio. Questa proprietà è di sola lettura e restituisce un ICaptionsCollection contenente tutte le tracce di sottotitoli.
type: docs
weight: 456
url: /it/aspose.slides/audioframe/get_captiontracks/
---
## AudioFrame::get_CaptionTracks() metodo


Ottiene la collezione di sottotitoli chiusi associati al frame audio. Questa proprietà è di sola lettura e restituisce un [ICaptionsCollection](../../icaptionscollection/) contenente tutte le tracce di sottotitoli.

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::AudioFrame::get_CaptionTracks() override
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
        // Salva i dati binari della traccia dei sottotitoli come file .vtt
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
* Classe [AudioFrame](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)