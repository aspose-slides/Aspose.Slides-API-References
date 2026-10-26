---
title: set_TrimFromStart()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan durasi waktu yang akan dihapus dari awal media selama pemutaran, dalam milidetik. Tulis float.
type: docs
weight: 417
url: /id/aspose.slides/audioframe/set_trimfromstart/
---
## AudioFrame::set_TrimFromStart(float) metode

Menentukan durasi waktu yang akan dihapus dari awal media selama pemutaran, dalam milidetik. Tulis **float**.

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromStart(float value) override
```

## Catatan

Contoh:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Tambah Bingkai Audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Atur waktu pemotongan awal 1.5 detik
audioFrame->set_TrimFromStart(1500.0f);
```

## Lihat Juga

* Kelas [AudioFrame](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)