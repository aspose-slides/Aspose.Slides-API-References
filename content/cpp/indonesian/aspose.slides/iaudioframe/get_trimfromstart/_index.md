---
title: get_TrimFromStart()
second_title: Aspose.Slides untuk Referensi API C++
description: Menentukan durasi waktu yang harus dihapus dari awal media selama pemutaran, dalam milidetik. Baca float.
type: docs
weight: 404
url: /id/aspose.slides/iaudioframe/get_trimfromstart/
---
## IAudioFrame::get_TrimFromStart() metode


Menentukan durasi waktu yang akan dihapus dari awal media selama pemutaran, dalam milidetik. Baca **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromStart()=0
```

## Catatan


Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Tambahkan Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Atur waktu pemotongan awal menjadi 1,5 detik
audioFrame->set_TrimFromStart(1500.0f);
```

## Lihat Juga

* Kelas [IAudioFrame](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)