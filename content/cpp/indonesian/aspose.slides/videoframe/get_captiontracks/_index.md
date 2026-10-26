---
title: get_CaptionTracks()
second_title: Aspose.Slides untuk Referensi API C++
description: Mendapatkan koleksi caption tertutup yang terkait dengan frame video. Properti ini hanya-baca dan mengembalikan sebuah ICaptionsCollection yang berisi semua trek caption.
type: docs
weight: 261
url: /id/aspose.slides/videoframe/get_captiontracks/
---
## VideoFrame::get_CaptionTracks() method


Mendapatkan koleksi caption tertutup yang terkait dengan frame video. Properti ini hanya-baca dan mengembalikan sebuah [ICaptionsCollection](../../icaptionscollection/) yang berisi semua trek caption.

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::VideoFrame::get_CaptionTracks() override
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
* Kelas [VideoFrame](../)
* Ruang nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)