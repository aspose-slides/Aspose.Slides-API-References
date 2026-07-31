---
title: get_CaptionTracks()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan koleksi caption tertutup yang terkait dengan bingkai audio. Properti ini bersifat hanya-baca dan mengembalikan sebuah ICaptionsCollection yang berisi semua trek caption.
type: docs
weight: 261
url: /id/aspose.slides/ivideoframe/get_captiontracks/
---
## IVideoFrame::get_CaptionTracks() metode

Mendapatkan koleksi caption tertutup yang terkait dengan bingkai audio. Properti ini bersifat hanya-baca dan mengembalikan sebuah [ICaptionsCollection](../../icaptionscollection/) yang berisi semua trek caption.

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IVideoFrame::get_CaptionTracks()=0
```

## Catatan

Contoh:
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
        // Mengekstrak data biner caption dan menyimpannya ke file
        System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
    }
}
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ICaptionsCollection](../../icaptionscollection/)
* Kelas [IVideoFrame](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)