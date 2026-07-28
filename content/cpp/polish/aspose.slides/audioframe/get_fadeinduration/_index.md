---
title: get_FadeInDuration()
second_title: Aspose.Slides dla C++ – Referencja API
description: Określa czas trwania początkowego płynnego włączenia mediów w milisekundach. Odczyt float.
type: docs
weight: 326
url: /pl/aspose.slides/audioframe/get_fadeinduration/
---
## AudioFrame::get_FadeInDuration() metoda


Określa czas trwania początkowego płynnego włączenia mediów w milisekundach. Odczyt **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeInDuration() override
```

## Uwagi


Przykład: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Dodaj ramkę audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Ustaw czas trwania początkowego zaniku na 200 ms
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Klasa [AudioFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)