---
title: set_PlayAcrossSlides()
second_title: Aspose.Slides için C++ API Referansı
description: Sesin slaytlar arasında çalınıp çalınmadığını belirler. bool yazın.
type: docs
weight: 222
url: /tr/aspose.slides/iaudioframe/set_playacrossslides/
---
## IAudioFrame::set_PlayAcrossSlides(bool) yöntemi


Sesin slaytlar arasında çalınıp çalınmadığını belirler. **bool** yazın.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_PlayAcrossSlides(bool value)=0
```

## Açıklamalar



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Ses Çerçevesi Ekle
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Sesin slaytlar arasında çalmasını ayarla
audioFrame->set_PlayAcrossSlides(true);

// Sesin çaldıktan sonra otomatik olarak başa sarmasını ayarla
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## Ayrıca Bakınız

* Sınıf [IAudioFrame](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)