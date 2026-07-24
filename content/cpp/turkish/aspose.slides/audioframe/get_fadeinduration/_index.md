---
title: get_FadeInDuration()
second_title: Aspose.Slides için C++ API Referansı
description: Medyanın ilk fade-in süresini milisaniye cinsinden belirtir. Okunur float.
type: docs
weight: 326
url: /tr/aspose.slides/audioframe/get_fadeinduration/
---
## AudioFrame::get_FadeInDuration() metodu


Medyanın ilk fade-in süresini milisaniye cinsinden belirtir. Okunur **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeInDuration() override
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Ses Çerçevesi Ekle
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Başlangıç fade süresini 200ms olarak ayarla
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Sınıf [AudioFrame](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)