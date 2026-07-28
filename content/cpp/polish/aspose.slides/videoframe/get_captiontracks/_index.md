---
title: get_CaptionTracks()
second_title: Aspose.Slides dla C++ – odwołanie API
description: Zwraca kolekcję zamkniętych napisów powiązanych z ramką wideo. Ta właściwość jest tylko do odczytu i zwraca ICaptionsCollection zawierający wszystkie ścieżki napisów.
type: docs
weight: 261
url: /pl/aspose.slides/videoframe/get_captiontracks/
---
## VideoFrame::get_CaptionTracks() metoda

Pobiera kolekcję napisów zamkniętych skojarzonych z ramką wideo. Ta własność jest tylko do odczytu i zwraca [ICaptionsCollection](../../icaptionscollection/) zawierający wszystkie ścieżki napisów.

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::VideoFrame::get_CaptionTracks() override
```

## Uwagi

Przykład: 
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
        // Ekstrahuje binarne dane napisów i zapisuje je do pliku
        System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
    }
}
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ICaptionsCollection](../../icaptionscollection/)
* Klasa [VideoFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)