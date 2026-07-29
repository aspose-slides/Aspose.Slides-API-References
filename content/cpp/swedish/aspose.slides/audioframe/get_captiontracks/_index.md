---
title: get_CaptionTracks()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar samlingen av stängda undertexter som är associerade med ljudramen. Egenskapen är skrivskyddad och returnerar en ICaptionsCollection som innehåller alla undertextspår.
type: docs
weight: 456
url: /sv/aspose.slides/audioframe/get_captiontracks/
---
## AudioFrame::get_CaptionTracks() metod


Hämtar samlingen av stängda undertexter som är associerade med ljudramen. Denna egenskap är skrivskyddad och returnerar en [ICaptionsCollection](../../icaptionscollection/) som innehåller alla undertextspår.

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::AudioFrame::get_CaptionTracks() override
```

## Anmärkningar


Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"audio with captions.pptx");
for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    if (System::ObjectExt::Is<IAudioFrame>(shape))
    {
        System::SharedPtr<IAudioFrame> audioFrame = System::ExplicitCast<IAudioFrame>(shape);
        // Spara undertextspårets binära data som en .vtt-fil
        for (auto&& captionTrack : audioFrame->get_CaptionTracks())
        {
            System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
        }
    }
}
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ICaptionsCollection](../../icaptionscollection/)
* Klass [AudioFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)