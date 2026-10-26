---
title: set_RewindAudio()
second_title: Aspose.Slides for C++ API Referansı
description: Bir sesin oynatıldıktan sonra otomatik olarak başlangıca sarılıp sarılmayacağını belirler. bool yazın.
type: docs
weight: 248
url: /tr/aspose.slides/iaudioframe/set_rewindaudio/
---
## IAudioFrame::set_RewindAudio(bool) metodu

Sesin oynatıldıktan sonra otomatik olarak başa sarılıp sarılmayacağını belirler. **bool** yazın.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_RewindAudio(bool value)=0
```

## Açıklamalar


```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Ses Çerçevesi Ekle
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Sesin slaytlar arasında çalmasını ayarla
audioFrame->set_PlayAcrossSlides(true);

// Sesin çalındıktan sonra otomatik olarak başa sarılmasını ayarla
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```



## Ayrıca Bakınız

* Sınıf [IAudioFrame](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)