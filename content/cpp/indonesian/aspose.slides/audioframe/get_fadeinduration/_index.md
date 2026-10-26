---
title: get_FadeInDuration()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan durasi waktu untuk fade-in awal media dalam milidetik. Baca float.
type: docs
weight: 326
url: /id/aspose.slides/audioframe/get_fadeinduration/
---
## AudioFrame::get_FadeInDuration() metode

Menentukan durasi waktu untuk fade-in awal media dalam milidetik. Baca **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeInDuration() override
```
## Catatan

Contoh:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Tambahkan Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Atur durasi fade awal selama 200ms
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```
## Lihat Juga

* Kelas [AudioFrame](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)