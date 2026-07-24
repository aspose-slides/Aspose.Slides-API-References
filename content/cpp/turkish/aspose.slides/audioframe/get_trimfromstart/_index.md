---
title: get_TrimFromStart()
second_title: Aspose.Slides için C++ API Referansı
description: Oynatma sırasında medyanın başından kaldırılacak zaman süresini milisaniye cinsinden belirtir. Okur **float**.
type: docs
weight: 404
url: /tr/aspose.slides/audioframe/get_trimfromstart/
---
## AudioFrame::get_TrimFromStart() metodu


Oynatma sırasında medyanın başından kaldırılacak zaman süresini milisaniye olarak belirtir. Okur **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromStart() override
```

## Açıklamalar


Örnek:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Audio Çerçevesi Ekle
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the start trimming time 1.5 seconds
audioFrame->set_TrimFromStart(1500.0f);
```

## Ayrıca Bakınız

* Sınıf [AudioFrame](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)