---
title: get_CaptionTracks()
second_title: Aspose.Slides pro rozhraní API C++
description: Získá kolekci uzavřených titulků spojených s video rámcem. Tato vlastnost je jen pro čtení a vrací ICaptionsCollection obsahující všechny stopy titulků.
type: docs
weight: 261
url: /cs/aspose.slides/videoframe/get_captiontracks/
---
## VideoFrame::get_CaptionTracks() metoda

Získá kolekci uzavřených titulků spojených s video rámečkem. Tato vlastnost je jen pro čtení a vrací [ICaptionsCollection](../../icaptionscollection/) obsahující všechny stopy titulků.

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::VideoFrame::get_CaptionTracks() override
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
        // Extrahuje binární data titulků a ukládá je do souboru
        System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
    }
}
```

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [ICaptionsCollection](../../icaptionscollection/)
* Třída [VideoFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)