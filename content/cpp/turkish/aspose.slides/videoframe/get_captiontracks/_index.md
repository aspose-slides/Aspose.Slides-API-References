---
title: get_CaptionTracks()
second_title: Aspose.Slides for C++ API Referansı
description: Video çerçevesiyle ilişkili kapalı altyazıların koleksiyonunu alır. Bu özellik sadece okuma amaçlıdır ve tüm altyazı izlerini içeren bir ICaptionsCollection döndürür.
type: docs
weight: 261
url: /tr/aspose.slides/videoframe/get_captiontracks/
---
## VideoFrame::get_CaptionTracks() metodu

Video çerçevesiyle ilişkili kapalı altyazıların koleksiyonunu alır. Bu özellik yalnızca okuma olup tüm altyazı izlerini içeren bir [ICaptionsCollection](../../icaptionscollection/) döndürür.

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::VideoFrame::get_CaptionTracks() override
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
        // Altyazıların ikili verilerini çıkarır ve dosyaya kaydeder
        System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
    }
}
```

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ICaptionsCollection](../../icaptionscollection/)
* Sınıf [VideoFrame](../)
* İsim Uzayı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)