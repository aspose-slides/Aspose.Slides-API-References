---
title: get_FadeOutDuration()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan durasi waktu untuk fade-out akhir media dalam milidetik. Baca float.
type: docs
weight: 352
url: /id/aspose.slides/audioframe/get_fadeoutduration/
---
## AudioFrame::get_FadeOutDuration() metode


Menentukan durasi waktu untuk fade-out akhir media dalam milidetik. Baca **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeOutDuration() override
```

## Catatan


Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Tambahkan Frame Audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the duration of the ending fade for 500ms
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Kelas [AudioFrame](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)