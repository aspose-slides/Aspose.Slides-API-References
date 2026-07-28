---
title: get_CaptionTracks()
second_title: Aspose.Slides C++ API-referencia
description: Lekéri a hangkerethez társított zárt feliratok gyűjteményét. Ez a tulajdonság csak olvasható, és egy ICaptionsCollection-t ad vissza, amely az összes feliratsávot tartalmazza.
type: docs
weight: 261
url: /hu/aspose.slides/ivideoframe/get_captiontracks/
---
## IVideoFrame::get_CaptionTracks() metódus

Lekéri a hangkerethez társított zárt feliratok gyűjteményét. Ez a tulajdonság csak olvasható, és egy [ICaptionsCollection](../../icaptionscollection/)-t ad vissza, amely az összes feliratsávot tartalmazza.

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IVideoFrame::get_CaptionTracks()=0
```

## Megjegyzések

Példa:
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
        // Kinyeri a feliratok bináris adatait, és elmenti a fájlba
        System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
    }
}
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICaptionsCollection](../../icaptionscollection/)
* Class [IVideoFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)