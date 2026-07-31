---
title: set_PlayAcrossSlides()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah audio diputar di seluruh slide. Tulis bool.
type: docs
weight: 222
url: /id/aspose.slides/audioframe/set_playacrossslides/
---
## AudioFrame::set_PlayAcrossSlides(bool) metode

Menentukan apakah audio diputar di seluruh slide. Tulis **bool**.

```cpp
void Aspose::Slides::AudioFrame::set_PlayAcrossSlides(bool value) override
```

## Catatan


```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Tambah Audio Frame
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Atur Audio agar diputar di seluruh slide
audioFrame->set_PlayAcrossSlides(true);

// Atur Audio agar otomatis kembali ke awal setelah diputar
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Lihat Juga

* Kelas [AudioFrame](../)
* RuangNama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)