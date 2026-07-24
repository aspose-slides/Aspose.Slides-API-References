---
title: set_TrimFromEnd()
second_title: Aspose.Slides for C++ API Referansı
description: Oynatma sırasında medyanın sonundan milisaniye cinsinden kaldırılacak zaman süresini belirtir. float yazın.
type: docs
weight: 443
url: /tr/aspose.slides/audioframe/set_trimfromend/
---
## AudioFrame::set_TrimFromEnd(float) yöntemi

Oynatma sırasında medyanın sonundan milisaniye cinsinden kaldırılacak zaman süresini belirtir. **float** yazın.

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromEnd(float value) override
```

## Açıklamalar

Örnek:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Ses Çerçevesi Ekle
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Son kırpma süresini 2 saniye ayarla
audioFrame->set_TrimFromEnd(2000.0f);
```

## Ayrıca Bakınız

* Sınıf [AudioFrame](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)