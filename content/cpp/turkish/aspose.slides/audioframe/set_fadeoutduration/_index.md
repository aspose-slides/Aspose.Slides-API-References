---
title: set_FadeOutDuration()
second_title: Aspose.Slides için C++ API Referansı
description: Ortamın sona eren fade-out süresini milisaniye cinsinden belirtir. float yazın.
type: docs
weight: 365
url: /tr/aspose.slides/audioframe/set_fadeoutduration/
---
## AudioFrame::set_FadeOutDuration(float) metodu


Ortamın sona eren fade-out süresi milisaniye cinsinden belirtilir. **float** yazın.

```cpp
void Aspose::Slides::AudioFrame::set_FadeOutDuration(float value) override
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Ses Çerçevesi Ekle
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 500ms için bitiş fade süresini ayarla
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Sınıf [AudioFrame](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)