---
title: get_CaptionTracks()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de verzameling van gesloten ondertitels op die bij het audioframe horen. Deze eigenschap is alleen-lezen en retourneert een ICaptionsCollection die alle ondertitelsporen bevat.
type: docs
weight: 456
url: /nl/aspose.slides/iaudioframe/get_captiontracks/
---
## IAudioFrame::get_CaptionTracks() methode


Haalt de verzameling van gesloten ondertitels op die bij het audioframe horen. Deze eigenschap is alleen-lezen en retourneert een [ICaptionsCollection](../../icaptionscollection/) die alle ondertitelsporen bevat.

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IAudioFrame::get_CaptionTracks()=0
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
        // Sla de binaire gegevens van het ondertitelspoor op als een .vtt-bestand
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
* Klasse [IAudioFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)