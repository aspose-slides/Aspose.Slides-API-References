---
title: get_CaptionTracks()
second_title: Aspose.Slides for C++ API Referencia
description: Lekéri a hangkerethez kapcsolódó zárt feliratok gyűjteményét. Ez a tulajdonság csak olvasható, és egy ICaptionsCollection objektumot ad vissza, amely az összes feliratsávot tartalmazza.
type: docs
weight: 456
url: /hu/aspose.slides/audioframe/get_captiontracks/
---
## AudioFrame::get_CaptionTracks() metódus


Lekéri a hangkerethez társított zárt feliratok gyűjteményét. Ez a tulajdonság csak olvasható, és egy [ICaptionsCollection](../../icaptionscollection/) objektumot ad vissza, amely az összes feliratsávot tartalmazza.

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::AudioFrame::get_CaptionTracks() override
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
        // Mentse a feliratsáv bináris adatát .vtt fájlként
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
* Osztály [AudioFrame](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)