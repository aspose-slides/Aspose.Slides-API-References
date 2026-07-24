---
title: get_FadeOutDuration()
second_title: Aspose.Slides için C++ API Referansı
description: Medyanın son fade-out süresini milisaniye cinsinden belirtir. Okunur float.
type: docs
weight: 352
url: /tr/aspose.slides/audioframe/get_fadeoutduration/
---
## AudioFrame::get_FadeOutDuration() yöntemi


Medyanın son fade-out süresini milisaniye cinsinden belirtir. Okunur **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeOutDuration() override
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Ses Çerçevesi Ekle
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Son fade-out süresini 500ms olarak ayarla
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Diğer Bağlantılar

* Sınıf [AudioFrame](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)