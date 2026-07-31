---
title: get_TrimFromEnd()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan durasi waktu yang akan dihapus dari akhir media selama pemutaran, dalam milidetik. Baca float.
type: docs
weight: 430
url: /id/aspose.slides/iaudioframe/get_trimfromend/
---
## IAudioFrame::get_TrimFromEnd() metode


Menentukan durasi waktu yang akan dihapus dari akhir media selama pemutaran, dalam milidetik. Baca **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromEnd()=0
```

## Catatan


Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Tambahkan Bingkai Audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Setel waktu pemangkasan akhir 2 detik
audioFrame->set_TrimFromEnd(2000.0f);
```

## Lihat Juga

* Kelas [IAudioFrame](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)