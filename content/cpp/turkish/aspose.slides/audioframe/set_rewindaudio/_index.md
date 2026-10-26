---
title: set_RewindAudio()
second_title: Aspose.Slides için C++ API Referansı
description: Sesin oynatıldıktan sonra otomatik olarak başa sarılıp sarılmayacağını belirler. bool yazın.
type: docs
weight: 248
url: /tr/aspose.slides/audioframe/set_rewindaudio/
---
## AudioFrame::set_RewindAudio(bool) yöntemi

Sesin oynatıldıktan sonra otomatik olarak başa sarılıp sarılmayacağını belirler. **bool** yazın.

```cpp
void Aspose::Slides::AudioFrame::set_RewindAudio(bool value) override
```

## Açıklamalar

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Add Audio Frame
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Set Audio to play across the slides
audioFrame->set_PlayAcrossSlides(true);

// Set Audio to automatically rewind to start after playing
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Sınıf [AudioFrame](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)