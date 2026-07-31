---
title: get_PlayAcrossSlides()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah audio diputar di seluruh slide. Baca bool.
type: docs
weight: 209
url: /id/aspose.slides/iaudioframe/get_playacrossslides/
---
## IAudioFrame::get_PlayAcrossSlides() metode


Menentukan apakah audio diputar di seluruh slide. Read **bool**.

```cpp
virtual bool Aspose::Slides::IAudioFrame::get_PlayAcrossSlides()=0
```

## Keterangan



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Tambahkan Frame Audio
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Atur Audio agar diputar di seluruh slide
audioFrame->set_PlayAcrossSlides(true);

// Atur Audio agar otomatis kembali ke awal setelah diputar
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## Lihat Juga

* Kelas [IAudioFrame](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)