---
title: get_VolumeValue()
second_title: Aspose.Slides için C++ API Referansı
description: Ses hacmini yüzde cinsinden döndürür. Okunan **float**.
type: docs
weight: 378
url: /tr/aspose.slides/iaudioframe/get_volumevalue/
---
## IAudioFrame::get_VolumeValue() yöntemi


Ses hacmini yüzde cinsinden döndürür. Okunan **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_VolumeValue()=0
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Ses Çerçevesi Ekle
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Başlangıç solma süresini 200ms olarak ayarla
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Diğer Bağlantılar

* Sınıf [IAudioFrame](../)
* İsim alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)