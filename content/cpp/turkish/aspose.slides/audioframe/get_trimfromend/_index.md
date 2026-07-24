---
title: get_TrimFromEnd()
second_title: Aspose.Slides C++ için API Referansı
description: Oynatma sırasında medyanın sonundan kaldırılacak zaman süresini milisaniye cinsinden belirtir. float okur.
type: docs
weight: 430
url: /tr/aspose.slides/audioframe/get_trimfromend/
---
## AudioFrame::get_TrimFromEnd() metodu

Specifies the time duration to be removed from the end of the media during playback, in milliseconds. Read **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromEnd() override
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

## Bakınız

* Class [AudioFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)