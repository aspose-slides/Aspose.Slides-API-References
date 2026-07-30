---
title: get_CaptionTracks()
second_title: Aspose.Slides pro C++ API Reference
description: Získá kolekci uzavřených titulků souvisejících s audio snímkem. Tato vlastnost je jen pro čtení a vrací ICaptionsCollection obsahující všechny stopy titulků.
type: docs
weight: 261
url: /cs/aspose.slides/ivideoframe/get_captiontracks/
---
## IVideoFrame::get_CaptionTracks() metoda

Získá kolekci uzavřených titulků souvisejících s audio snímkem. Tato vlastnost je jen pro čtení a vrací [ICaptionsCollection](../../icaptionscollection/) obsahující všechny stopy titulků.

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IVideoFrame::get_CaptionTracks()=0
```

## Poznámky

Příklad:
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
        // Extrahuje binární data titulků a uloží je do souboru
        System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
    }
}
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [ICaptionsCollection](../../icaptionscollection/)
* třída [IVideoFrame](../)
* jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)