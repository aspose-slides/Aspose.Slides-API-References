---
title: get_TrimFromStart()
second_title: Aspose.Slides için C++ API Referansı
description: Oynatma sırasında medyanın başından kaldırılacak zaman süresini milisaniye cinsinden belirtir. float okunur.
type: docs
weight: 404
url: /tr/aspose.slides/iaudioframe/get_trimfromstart/
---
## IAudioFrame::get_TrimFromStart() metodu


Medyanın oynatma sırasında başından kaldırılacak zaman süresini milisaniye cinsinden belirtir. **float** okunur.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromStart()=0
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

## İlgili

* Sınıf [IAudioFrame](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)