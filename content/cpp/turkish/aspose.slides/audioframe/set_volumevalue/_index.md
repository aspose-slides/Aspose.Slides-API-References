---
title: set_VolumeValue()
second_title: C++ için Aspose.Slides API Referansı
description: Ses seviyesini yüzde olarak ayarlar. Float yazın.
type: docs
weight: 391
url: /tr/aspose.slides/audioframe/set_volumevalue/
---
## AudioFrame::set_VolumeValue(float) method


Ses seviyesini yüzde olarak ayarlar. **float** yazın.

```cpp
void Aspose::Slides::AudioFrame::set_VolumeValue(float value) override
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Ses Çerçevesi Ekle
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Başlangıç solma süresini 200 ms olarak ayarla
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Sınıf [AudioFrame](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)