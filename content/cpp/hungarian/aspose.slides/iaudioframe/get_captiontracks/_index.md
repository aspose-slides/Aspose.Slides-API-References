---
title: get_CaptionTracks()
second_title: Aspose.Slides C++ API-referencia
description: Lekéri a hangkerethez kapcsolódó zárt feliratok gyűjteményét. Ez a tulajdonság csak olvasható, és egy ICaptionsCollection-t ad vissza, amely az összes feliratsávot tartalmazza.
type: docs
weight: 456
url: /hu/aspose.slides/iaudioframe/get_captiontracks/
---
## IAudioFrame::get_CaptionTracks() metódus

Lekéri a hangkerethez tartozó zárt feliratok gyűjteményét. Ez a tulajdonság csak olvasható, és egy [ICaptionsCollection](../../icaptionscollection/)-t ad vissza, amely az összes feliratsávot tartalmazza.

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IAudioFrame::get_CaptionTracks()=0
```

## Megjegyzések

Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"audio with captions.pptx");
for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    if (System::ObjectExt::Is<IAudioFrame>(shape))
    {
        System::SharedPtr<IAudioFrame> audioFrame = System::ExplicitCast<IAudioFrame>(shape);
        // Mentse a feliratsáv bináris adatait .vtt fájlként
        for (auto&& captionTrack : audioFrame->get_CaptionTracks())
        {
            System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
        }
    }
}
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ICaptionsCollection](../../icaptionscollection/)
* Osztály [IAudioFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)