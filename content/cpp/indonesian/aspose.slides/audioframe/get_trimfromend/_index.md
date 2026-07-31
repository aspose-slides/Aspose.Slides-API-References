---
title: get_TrimFromEnd()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan durasi waktu yang akan dihapus dari akhir media selama pemutaran, dalam milidetik. Baca float.
type: docs
weight: 430
url: /id/aspose.slides/audioframe/get_trimfromend/
---
## AudioFrame::get_TrimFromEnd() metode


Menentukan durasi waktu yang akan dihapus dari akhir media selama pemutaran, dalam milidetik. Baca **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromEnd() override
```

## Keterangan


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
* RuangNama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)