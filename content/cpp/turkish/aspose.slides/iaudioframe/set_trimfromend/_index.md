---
title: set_TrimFromEnd()
second_title: Aspose.Slides için C++ API Referansı
description: Oynatma sırasında medyanın sonundan kaldırılması gereken zaman süresini milisaniye cinsinden belirtir. float yazın.
type: docs
weight: 443
url: /tr/aspose.slides/iaudioframe/set_trimfromend/
---
## IAudioFrame::set_TrimFromEnd(float) metod

Oynatma sırasında medyanın sonundan kaldırılması gereken zaman süresini milisaniye cinsinden belirtir. **float** yazın.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromEnd(float value)=0
```

## Açıklamalar

Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Ses Çerçevesi Ekle
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Son kırpma süresini 2 saniye olarak ayarla
audioFrame->set_TrimFromEnd(2000.0f);
```

## İlgili

* Sınıf [IAudioFrame](../)
* İsim Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)