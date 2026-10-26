---
title: get_CaptionTracks()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Získá kolekci uzavřených titulků spojených s audio snímkem. Tato vlastnost je pouze pro čtení a vrací ICaptionsCollection obsahující všechny stopy titulků.
type: docs
weight: 456
url: /cs/aspose.slides/audioframe/get_captiontracks/
---
## AudioFrame::get_CaptionTracks() metoda

Získá kolekci uzavřených titulků spojených s audio snímkem. Tato vlastnost je pouze pro čtení a vrací [ICaptionsCollection](../../icaptionscollection/) obsahující všechny stopy titulků.

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::AudioFrame::get_CaptionTracks() override
```

## Poznámky

Příklad:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"audio with captions.pptx");
for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    if (System::ObjectExt::Is<IAudioFrame>(shape))
    {
        System::SharedPtr<IAudioFrame> audioFrame = System::ExplicitCast<IAudioFrame>(shape);
        // Uložte binární data stopy titulků jako .vtt soubor
        for (auto&& captionTrack : audioFrame->get_CaptionTracks())
        {
            System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
        }
    }
}
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ICaptionsCollection](../../icaptionscollection/)
* Třída [AudioFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)