---
title: get_CaptionTracks()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce la collezione di sottotitoli chiusi associati al fotogramma audio. Questa proprietà è di sola lettura e restituisce una ICaptionsCollection contenente tutte le tracce di sottotitoli.
type: docs
weight: 261
url: /it/aspose.slides/ivideoframe/get_captiontracks/
---
## IVideoFrame::get_CaptionTracks() metodo

Restituisce la collezione di sottotitoli chiusi associati al fotogramma audio. Questa proprietà è di sola lettura e restituisce un [ICaptionsCollection](../../icaptionscollection/) contenente tutte le tracce di sottotitoli.

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IVideoFrame::get_CaptionTracks()=0
```

## Osservazioni

Esempio:
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
        // Estrae i dati binari dei sottotitoli e li salva nel file
        System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
    }
}
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ICaptionsCollection](../../icaptionscollection/)
* Classe [IVideoFrame](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)