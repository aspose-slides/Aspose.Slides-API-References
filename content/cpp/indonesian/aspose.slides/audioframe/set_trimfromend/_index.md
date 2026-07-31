---
title: set_TrimFromEnd()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan durasi waktu yang akan dihapus dari akhir media selama pemutaran, dalam milidetik. Tulis float.
type: docs
weight: 443
url: /id/aspose.slides/audioframe/set_trimfromend/
---
## AudioFrame::set_TrimFromEnd(float) metode

Menentukan durasi waktu yang akan dihapus dari akhir media selama pemutaran, dalam milidetik. Tulis **float**.

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromEnd(float value) override
```

## Catatan

Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Tambahkan Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Atur waktu pemangkasan akhir 2 detik
audioFrame->set_TrimFromEnd(2000.0f);
```

## Lihat Juga

* Kelas [AudioFrame](../)
* Namespace [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)