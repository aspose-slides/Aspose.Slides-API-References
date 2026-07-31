---
title: set_RewindAudio()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah audio secara otomatis diputar kembali ke awal setelah diputar. Tulis bool.
type: docs
weight: 248
url: /id/aspose.slides/audioframe/set_rewindaudio/
---
## AudioFrame::set_RewindAudio(bool) metode

Menentukan apakah audio secara otomatis diputar kembali ke awal setelah diputar. Tuliskan **bool**.

```cpp
void Aspose::Slides::AudioFrame::set_RewindAudio(bool value) override
```

## Catatan

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Tambahkan Audio Frame
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Set Audio untuk diputar di seluruh slide
audioFrame->set_PlayAcrossSlides(true);

// Set Audio untuk secara otomatis kembali ke awal setelah diputar
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Lihat Juga

* Kelas [AudioFrame](../)
* Namespace [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)