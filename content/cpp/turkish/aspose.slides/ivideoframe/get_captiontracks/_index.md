---
title: get_CaptionTracks()
second_title: Aspose.Slides için C++ API Referansı
description: Ses çerçevesiyle ilişkili kapalı altyazıların koleksiyonunu alır. Bu özellik salt okunur ve tüm altyazı izlerini içeren bir ICaptionsCollection döndürür.
type: docs
weight: 261
url: /tr/aspose.slides/ivideoframe/get_captiontracks/
---
## IVideoFrame::get_CaptionTracks() metodu


Ses çerçevesiyle ilişkili kapalı altyazıların koleksiyonunu alır. Bu özellik salt okunur ve tüm altyazı izlerini içeren bir [ICaptionsCollection](../../icaptionscollection/) döndürür.

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IVideoFrame::get_CaptionTracks()=0
```

## Açıklamalar


Örnek: 
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
        // Altyazıların ikili verisini çıkarır ve dosyaya kaydeder
        System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
    }
}
```

## Ayrıca bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ICaptionsCollection](../../icaptionscollection/)
* Sınıf [IVideoFrame](../)
* Ad alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)