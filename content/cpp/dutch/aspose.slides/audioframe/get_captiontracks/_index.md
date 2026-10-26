---
title: get_CaptionTracks()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de collectie van gesloten bijschriften op die bij de audioframe horen. Deze eigenschap is alleen-lezen en retourneert een ICaptionsCollection die alle bijschriftsporen bevat.
type: docs
weight: 456
url: /nl/aspose.slides/audioframe/get_captiontracks/
---
## AudioFrame::get_CaptionTracks() methode


Haalt de verzameling van gesloten bijschriften op die bij het audioframe horen. Deze eigenschap is alleen-lezen en retourneert een [ICaptionsCollection](../../icaptionscollection/) die alle bijschriftsporen bevat.

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::AudioFrame::get_CaptionTracks() override
```

## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"audio with captions.pptx");
for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    if (System::ObjectExt::Is<IAudioFrame>(shape))
    {
        System::SharedPtr<IAudioFrame> audioFrame = System::ExplicitCast<IAudioFrame>(shape);
        // Sla de binaire gegevens van het bijschriftspoor op als een .vtt-bestand
        for (auto&& captionTrack : audioFrame->get_CaptionTracks())
        {
            System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
        }
    }
}
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ICaptionsCollection](../../icaptionscollection/)
* Klasse [AudioFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)