---
title: get_CaptionTracks()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de collectie van gesloten ondertitels op die aan het audioframe zijn gekoppeld. Deze eigenschap is alleen-lezen en retourneert een ICaptionsCollection die alle ondertitelsporen bevat.
type: docs
weight: 261
url: /nl/aspose.slides/ivideoframe/get_captiontracks/
---
## IVideoFrame::get_CaptionTracks() methode

Haalt de collectie van gesloten bijschriften op die aan het audio frame gekoppeld zijn. Deze eigenschap is alleen-lezen en retourneert een [ICaptionsCollection](../../icaptionscollection/) die alle ondertitelsporen bevat.

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IVideoFrame::get_CaptionTracks()=0
```

## Opmerkingen

Voorbeeld: 
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
        // Extraheert de binaire ondertitelgegevens en slaat ze op in het bestand
        System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
    }
}
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ICaptionsCollection](../../icaptionscollection/)
* Klasse [IVideoFrame](../)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)