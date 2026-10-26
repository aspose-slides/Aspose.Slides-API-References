---
title: set_TrimFromStart()
second_title: Aspose.Slides için C++ API Referansı
description: Çalma sırasında medyanın başlangıcından kaldırılacak zaman süresini milisaniye cinsinden belirtir. float yazın.
type: docs
weight: 417
url: /tr/aspose.slides/audioframe/set_trimfromstart/
---
## AudioFrame::set_TrimFromStart(float) yöntemi

Çalma sırasında medyanın başlangıcından kaldırılacak zaman süresini milisaniye olarak belirtir. **float** yazın.

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromStart(float value) override
```

## Açıklamalar

Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Ses Çerçevesi Ekle
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Başlangıç kırpma süresini 1.5 saniyeye ayarla
audioFrame->set_TrimFromStart(1500.0f);
```

## Ayrıca Bakınız

* Sınıf [AudioFrame](../)
* İsim Uzayı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)