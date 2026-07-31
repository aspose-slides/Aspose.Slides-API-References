---
title: get_PlayAcrossSlides()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah audio diputar melintasi slide. Baca bool.
type: docs
weight: 209
url: /id/aspose.slides/audioframe/get_playacrossslides/
---
## AudioFrame::get_PlayAcrossSlides() metode

Menentukan apakah audio diputar melintasi slide. Baca **bool**.

```cpp
bool Aspose::Slides::AudioFrame::get_PlayAcrossSlides() override
```

## Catatan

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Tambahkan Audio Frame
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Atur Audio agar diputar melintasi slide
audioFrame->set_PlayAcrossSlides(true);

// Atur Audio agar secara otomatis kembali ke awal setelah diputar
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Lihat Juga

* Kelas [AudioFrame](../)
* Ruang nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)