---
title: set_PlayAcrossSlides()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah audio diputar di seluruh slide. Tulis bool.
type: docs
weight: 222
url: /id/aspose.slides/iaudioframe/set_playacrossslides/
---
## IAudioFrame::set_PlayAcrossSlides(bool) metode


Menentukan apakah audio diputar di seluruh slide. Tulis **bool**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_PlayAcrossSlides(bool value)=0
```

## Catatan



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Tambahkan Bingkai Audio
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Set Audio to play across the slides
audioFrame->set_PlayAcrossSlides(true);

// Set Audio to automatically rewind to start after playing
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## Lihat Juga

* Kelas [IAudioFrame](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)