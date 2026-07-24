---
title: get_CaptionTracks()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft die Sammlung geschlossener Untertitel ab, die dem Audio-Frame zugeordnet sind. Diese Eigenschaft ist schreibgeschützt und gibt eine ICaptionsCollection zurück, die alle Untertitelspuren enthält.
type: docs
weight: 456
url: /de/aspose.slides/audioframe/get_captiontracks/
---
## AudioFrame::get_CaptionTracks() Methode


Ruft die Sammlung geschlossener Untertitel ab, die dem Audio-Frame zugeordnet sind. Diese Eigenschaft ist schreibgeschützt und gibt ein [ICaptionsCollection](../../icaptionscollection/) zurück, das alle Untertitelspuren enthält.

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::AudioFrame::get_CaptionTracks() override
```

## Hinweise


Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"audio with captions.pptx");
for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    if (System::ObjectExt::Is<IAudioFrame>(shape))
    {
        System::SharedPtr<IAudioFrame> audioFrame = System::ExplicitCast<IAudioFrame>(shape);
        // Speichern Sie die Binärdaten der Untertitelspur als .vtt-Datei
        for (auto&& captionTrack : audioFrame->get_CaptionTracks())
        {
            System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
        }
    }
}
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ICaptionsCollection](../../icaptionscollection/)
* Klasse [AudioFrame](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)