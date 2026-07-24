---
title: get_TrimFromEnd()
second_title: Aspose.Slides for C++ API Referansı
description: Oynatma sırasında medyanın sonundan kaldırılacak süreyi milisaniye cinsinden belirtir. Okur float.
type: docs
weight: 430
url: /tr/aspose.slides/iaudioframe/get_trimfromend/
---
## IAudioFrame::get_TrimFromEnd() metod


Medyanın oynatma sırasında sonundan kaldırılacak süreyi milisaniye cinsinden belirtir. Okur **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromEnd()=0
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Audio Frame Ekle
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Son kırpma süresini 2 saniye olarak ayarla
audioFrame->set_TrimFromEnd(2000.0f);
```

## Ayrıca Bakınız

* Sınıf [IAudioFrame](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)