---
title: get_CaptionTracks()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft die Sammlung geschlossener Untertitel ab, die dem Video-Frame zugeordnet sind. Diese Eigenschaft ist schreibgeschützt und gibt eine ICaptionsCollection zurück, die alle Untertitelspuren enthält.
type: docs
weight: 261
url: /de/aspose.slides/videoframe/get_captiontracks/
---
## VideoFrame::get_CaptionTracks() Methode

Ruft die Sammlung geschlossener Untertitel ab, die mit dem Video-Frame verknüpft sind. Diese Eigenschaft ist schreibgeschützt und gibt ein [ICaptionsCollection](../../icaptionscollection/) zurück, das alle Untertitelspuren enthält.

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::VideoFrame::get_CaptionTracks() override
```

## Anmerkungen

Beispiel:
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
        // Extrahiert die Binärdaten der Untertitel und speichert sie in die Datei
        System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
    }
}
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICaptionsCollection](../../icaptionscollection/)
* Class [VideoFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)