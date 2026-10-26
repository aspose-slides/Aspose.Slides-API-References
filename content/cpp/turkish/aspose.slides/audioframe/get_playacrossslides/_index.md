---
title: get_PlayAcrossSlides()
second_title: Aspose.Slides için C++ API Referansı
description: Sesin slaytlar boyunca oynatılıp oynatılmadığını belirler. bool okunur.
type: docs
weight: 209
url: /tr/aspose.slides/audioframe/get_playacrossslides/
---
## AudioFrame::get_PlayAcrossSlides() yöntemi


Sesin slaytlar boyunca oynatılıp oynatılmadığını belirler. Okur **bool**.

```cpp
bool Aspose::Slides::AudioFrame::get_PlayAcrossSlides() override
```

## Açıklamalar



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Ses Çerçevesi Ekle
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Sesin slaytlar boyunca çalmasını ayarla
audioFrame->set_PlayAcrossSlides(true);

// Sesin çaldıktan sonra otomatik olarak başa sarmasını ayarla
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Ayrıca bakınız

* Sınıf [AudioFrame](../)
* İsim alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)