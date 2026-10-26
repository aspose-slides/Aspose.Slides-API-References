---
title: get_RewindAudio()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah audio secara otomatis diputar ulang ke awal setelah diputar. Baca bool.
type: docs
weight: 235
url: /id/aspose.slides/audioframe/get_rewindaudio/
---
## AudioFrame::get_RewindAudio() metode

Menentukan apakah audio secara otomatis diputar ulang ke awal setelah diputar. Baca **bool**.

```cpp
bool Aspose::Slides::AudioFrame::get_RewindAudio() override
```

## Catatan


```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Add Audio Frame
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Set Audio to play across the slides
audioFrame->set_PlayAcrossSlides(true);

// Set Audio to automatically rewind to start after playing
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Lihat Juga

* Kelas [AudioFrame](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)