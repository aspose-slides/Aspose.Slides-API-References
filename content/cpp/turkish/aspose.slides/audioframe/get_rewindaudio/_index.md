---
title: get_RewindAudio()
second_title: C++ API Referansı için Aspose.Slides
description: Oynatıldıktan sonra sesin otomatik olarak başa sarılıp sarılmayacağını belirler. Okunur **bool**.
type: docs
weight: 235
url: /tr/aspose.slides/audioframe/get_rewindaudio/
---
## AudioFrame::get_RewindAudio() metod


Oynatıldıktan sonra sesin otomatik olarak başa sarılıp sarılmayacağını belirler. Okunur **bool**.

```cpp
bool Aspose::Slides::AudioFrame::get_RewindAudio() override
```

## Açıklamalar



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Ses Çerçevesi Ekle
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Sesin slaytlar arasında çalmasını ayarla
audioFrame->set_PlayAcrossSlides(true);

// Sesin oynatıldıktan sonra otomatik olarak başa sarılmasını ayarla
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Sınıf [AudioFrame](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)