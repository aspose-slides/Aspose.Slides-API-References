---
title: get_VolumeValue()
second_title: Aspose.Slides for C++ – Dokumentacja API
description: Zwraca głośność dźwięku w procentach. Odczyt float.
type: docs
weight: 378
url: /pl/aspose.slides/audioframe/get_volumevalue/
---
## AudioFrame::get_VolumeValue() metoda


Zwraca głośność dźwięku w procentach. Odczyt **float**.

```cpp
float Aspose::Slides::AudioFrame::get_VolumeValue() override
```

## Uwagi


Przykład:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Dodaj ramkę audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Ustaw czas trwania początkowego zanikania na 200 ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Klasa [AudioFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)