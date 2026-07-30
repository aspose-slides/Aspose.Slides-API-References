---
title: get_CaptionTracks()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Získá kolekci uzavřených titulků souvisejících s audio rámcem. Tato vlastnost je pouze pro čtení a vrací ICaptionsCollection obsahující všechny stopy titulků.
type: docs
weight: 456
url: /cs/aspose.slides/iaudioframe/get_captiontracks/
---
## IAudioFrame::get_CaptionTracks() metoda

Získá kolekci uzavřených titulků spojených s audio rámcem. Tato vlastnost je pouze pro čtení a vrací [ICaptionsCollection](../../icaptionscollection/) obsahující všechny stopy titulků.

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IAudioFrame::get_CaptionTracks()=0
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
        // Uložte binární data stopy titulků do souboru .vtt
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
* Třída [IAudioFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)