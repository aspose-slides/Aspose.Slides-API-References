---
title: get_CaptionTracks()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar samlingen av stängda undertexter som är associerade med ljudramen. Denna egenskap är skrivskyddad och returnerar en ICaptionsCollection som innehåller alla undertextspår.
type: docs
weight: 261
url: /sv/aspose.slides/ivideoframe/get_captiontracks/
---
## IVideoFrame::get_CaptionTracks() metod

Hämtar samlingen av stängda undertexter som är associerade med ljudramen. Denna egenskap är skrivskyddad och returnerar en [ICaptionsCollection](../../icaptionscollection/) som innehåller alla undertextspår.

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IVideoFrame::get_CaptionTracks()=0
```

## Anmärkningar


Exempel:
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
        // Extraherar undertexternas binära data och sparar dem till filen
        System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
    }
}
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ICaptionsCollection](../../icaptionscollection/)
* Klass [IVideoFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)