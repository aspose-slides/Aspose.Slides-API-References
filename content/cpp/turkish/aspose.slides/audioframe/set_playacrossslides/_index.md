---
title: set_PlayAcrossSlides()
second_title: Aspose.Slides için C++ API Referansı
description: Sesin slaytlar arasında çalınıp çalınmadığını belirler. bool yazın.
type: docs
weight: 222
url: /tr/aspose.slides/audioframe/set_playacrossslides/
---
## AudioFrame::set_PlayAcrossSlides(bool) yöntemi


Sesin slaytlar arasında çalınıp çalınmadığını belirler. **bool** yazın.

```cpp
void Aspose::Slides::AudioFrame::set_PlayAcrossSlides(bool value) override
```

## Açıklamalar



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Audio Çerçevesi ekle
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Sesin slaytlar arasında çalmasını ayarla
audioFrame->set_PlayAcrossSlides(true);

// Sesin oynatıldıktan sonra otomatik olarak başa sarmasını ayarla
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Ayrıca

* Sınıf [AudioFrame](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)