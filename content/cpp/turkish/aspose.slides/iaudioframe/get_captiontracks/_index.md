---
title: get_CaptionTracks()
second_title: Aspose.Slides for C++ API Referansı
description: Ses çerçevesiyle ilişkili kapalı altyazıların koleksiyonunu alır. Bu özellik yalnızca okunabilir ve tüm altyazı izlerini içeren bir ICaptionsCollection döndürür.
type: docs
weight: 456
url: /tr/aspose.slides/iaudioframe/get_captiontracks/
---
## IAudioFrame::get_CaptionTracks() metot

Ses çerçevesiyle ilişkili kapalı altyazıların koleksiyonunu alır. Bu özellik yalnızca okunabilir ve tüm altyazı izlerini içeren bir [ICaptionsCollection](../../icaptionscollection/) döndürür.

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IAudioFrame::get_CaptionTracks()=0
```

## Açıklamalar

Örnek:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"audio with captions.pptx");
for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    if (System::ObjectExt::Is<IAudioFrame>(shape))
    {
        System::SharedPtr<IAudioFrame> audioFrame = System::ExplicitCast<IAudioFrame>(shape);
        // Altyazı izinin ikili verisini .vtt dosyası olarak kaydet
        for (auto&& captionTrack : audioFrame->get_CaptionTracks())
        {
            System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
        }
    }
}
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ICaptionsCollection](../../icaptionscollection/)
* Sınıf [IAudioFrame](../)
* İsim Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)