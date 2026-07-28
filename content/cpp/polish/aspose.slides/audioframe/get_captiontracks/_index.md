---
title: get_CaptionTracks()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Pobiera kolekcję zamkniętych napisów powiązanych z klatką audio. Ta właściwość jest tylko do odczytu i zwraca ICaptionsCollection zawierający wszystkie ścieżki napisów.
type: docs
weight: 456
url: /pl/aspose.slides/audioframe/get_captiontracks/
---
## AudioFrame::get_CaptionTracks() metoda

Pobiera kolekcję zamkniętych napisów powiązanych z klatką audio. Ta właściwość jest tylko do odczytu i zwraca [ICaptionsCollection](../../icaptionscollection/) zawierający wszystkie ścieżki napisów.

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::AudioFrame::get_CaptionTracks() override
```

## Uwagi

Przykład:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"audio with captions.pptx");
for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    if (System::ObjectExt::Is<IAudioFrame>(shape))
    {
        System::SharedPtr<IAudioFrame> audioFrame = System::ExplicitCast<IAudioFrame>(shape);
        // Zapisz binarne dane ścieżki napisów jako plik .vtt
        for (auto&& captionTrack : audioFrame->get_CaptionTracks())
        {
            System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
        }
    }
}
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ICaptionsCollection](../../icaptionscollection/)
* Klasa [AudioFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)