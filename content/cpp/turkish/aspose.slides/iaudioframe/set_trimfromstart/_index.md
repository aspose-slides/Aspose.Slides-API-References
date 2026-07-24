---
title: set_TrimFromStart()
second_title: Aspose.Slides için C++ API Referansı
description: Medyanın oynatma sırasında başlangıcından kaldırılacak zaman süresini milisaniye cinsinden belirtir. Yazın float.
type: docs
weight: 417
url: /tr/aspose.slides/iaudioframe/set_trimfromstart/
---
## IAudioFrame::set_TrimFromStart(float) metot

Belirtilen süre, medya oynatılırken başlangıcından kaldırılacak zaman süresini milisaniye cinsinden belirtir. Yazın **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromStart(float value)=0
```

## Açıklamalar

Örnek:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Ses Çerçevesi Ekle
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Başlangıç kırpma süresini 1.5 saniye olarak ayarla
audioFrame->set_TrimFromStart(1500.0f);
```

## Bakınız

* Sınıf [IAudioFrame](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)