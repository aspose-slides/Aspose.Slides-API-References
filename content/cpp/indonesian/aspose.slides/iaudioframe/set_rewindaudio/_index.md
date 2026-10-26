---
title: set_RewindAudio()
second_title: Aspose.Slides untuk Referensi API C++
description: Menentukan apakah audio secara otomatis diputar ulang ke awal setelah diputar. Tulis bool.
type: docs
weight: 248
url: /id/aspose.slides/iaudioframe/set_rewindaudio/
---
## IAudioFrame::set_RewindAudio(bool) metode


Menentukan apakah audio secara otomatis diputar ulang ke awal setelah diputar. Tulis **bool**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_RewindAudio(bool value)=0
```

## Catatan



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Tambahkan Audio Frame
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Atur Audio untuk diputar di seluruh slide
audioFrame->set_PlayAcrossSlides(true);

// Atur Audio agar secara otomatis diputar ulang ke awal setelah diputar
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## Lihat Juga

* Kelas [IAudioFrame](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)