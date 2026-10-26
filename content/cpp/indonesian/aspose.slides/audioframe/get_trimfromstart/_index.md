---
title: get_TrimFromStart()
second_title: Aspose.Slides untuk Referensi API C++
description: Menentukan durasi waktu yang akan dihapus dari awal media selama pemutaran, dalam milidetik. Baca float.
type: docs
weight: 404
url: /id/aspose.slides/audioframe/get_trimfromstart/
---
## AudioFrame::get_TrimFromStart() method


Menentukan durasi waktu yang akan dihapus dari awal media selama pemutaran, dalam milidetik. Baca **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromStart() override
```

## Keterangan


Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Tambahkan Frame Audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Atur waktu pemangkasan awal 1.5 detik
audioFrame->set_TrimFromStart(1500.0f);
```

## Lihat Juga

* Kelas [AudioFrame](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)