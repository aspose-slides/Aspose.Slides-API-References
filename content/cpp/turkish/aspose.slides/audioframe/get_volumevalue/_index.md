---
title: get_VolumeValue()
second_title: Aspose.Slides for C++ API Referansı
description: Ses hacmini yüzde olarak döndürür. Okur float.
type: docs
weight: 378
url: /tr/aspose.slides/audioframe/get_volumevalue/
---
## AudioFrame::get_VolumeValue() metot


Ses hacmini yüzde olarak döndürür. Okur **float**.

```cpp
float Aspose::Slides::AudioFrame::get_VolumeValue() override
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

## Bakınız

* Sınıf [AudioFrame](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)