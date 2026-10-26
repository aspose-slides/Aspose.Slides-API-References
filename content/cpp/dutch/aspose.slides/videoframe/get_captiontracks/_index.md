---
title: get_CaptionTracks()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de collectie van gesloten ondertitels op die bij het videoframe horen. Deze eigenschap is alleen-lezen en retourneert een ICaptionsCollection met alle ondertitelingssporen.
type: docs
weight: 261
url: /nl/aspose.slides/videoframe/get_captiontracks/
---
## VideoFrame::get_CaptionTracks() methode


Haalt de collectie van gesloten ondertitels op die bij het videoframe horen. Deze eigenschap is alleen-lezen en retourneert een [ICaptionsCollection](../../icaptionscollection/) met alle ondertitelingstracks.

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::VideoFrame::get_CaptionTracks() override
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
        // Extraheert de binaire ondertiteldata en slaat deze op in het bestand
        System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
    }
}
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ICaptionsCollection](../../icaptionscollection/)
* Klasse [VideoFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)