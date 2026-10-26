---
title: get_Audios()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengembalikan koleksi semua file audio tersemat dalam presentasi. Hanya-baca IAudioCollection.
type: docs
weight: 222
url: /id/aspose.slides/presentation/get_audios/
---
## Presentation::get_Audios() metode

Mengembalikan koleksi semua file audio tersemat dalam presentasi. Hanya-baca [IAudioCollection](../../iaudiocollection/).

```cpp
System::SharedPtr<IAudioCollection> Aspose::Slides::Presentation::get_Audios() override
```

## Catatan

Contoh berikut menunjukkan cara menambahkan hyperlink ke file audio.

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"audio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(10.0f, 10.0f, 100.0f, 100.0f, audio);
audioFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
audioFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IAudioCollection](../../iaudiocollection/)
* Kelas [Presentation](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)