---
title: get_CaptionTracks()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan koleksi caption tertutup yang terkait dengan frame audio. Properti ini hanya-baca dan mengembalikan sebuah ICaptionsCollection yang berisi semua trek caption.
type: docs
weight: 456
url: /id/aspose.slides/audioframe/get_captiontracks/
---
## AudioFrame::get_CaptionTracks() metode


Mendapatkan koleksi teks tertutup yang terkait dengan audio frame. Properti ini hanya-baca dan mengembalikan sebuah [ICaptionsCollection](../../icaptionscollection/) yang berisi semua trek caption.

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::AudioFrame::get_CaptionTracks() override
```

## Catatan


Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"audio with captions.pptx");
for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    if (System::ObjectExt::Is<IAudioFrame>(shape))
    {
        System::SharedPtr<IAudioFrame> audioFrame = System::ExplicitCast<IAudioFrame>(shape);
        // Simpan data biner trek caption sebagai file .vtt
        for (auto&& captionTrack : audioFrame->get_CaptionTracks())
        {
            System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
        }
    }
}
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ICaptionsCollection](../../icaptionscollection/)
* Kelas [AudioFrame](../)
* Ruang nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)