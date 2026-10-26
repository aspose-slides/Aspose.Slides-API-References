---
title: set_TrimFromStart()
second_title: Aspose.Slides untuk Referensi API C++
description: Menentukan durasi waktu yang harus dihapus dari awal media selama pemutaran, dalam milidetik. Tulis float.
type: docs
weight: 417
url: /id/aspose.slides/iaudioframe/set_trimfromstart/
---
## IAudioFrame::set_TrimFromStart(float) metode


Menentukan durasi waktu yang harus dihapus dari awal media selama pemutaran, dalam milidetik. Tulis **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromStart(float value)=0
```

## Catatan


Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Tambahkan Bingkai Audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Atur waktu pemangkasan mulai 1,5 detik
audioFrame->set_TrimFromStart(1500.0f);
```

## Lihat Juga

* Kelas [IAudioFrame](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)