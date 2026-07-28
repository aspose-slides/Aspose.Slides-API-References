---
title: get_FadeOutDuration()
second_title: Aspose.Slides dla C++ - referencja API
description: Określa czas trwania końcowego wyciszenia mediów w milisekundach. Odczyt float.
type: docs
weight: 352
url: /pl/aspose.slides/audioframe/get_fadeoutduration/
---
## AudioFrame::get_FadeOutDuration() metoda


Określa czas trwania końcowego wyciszenia mediów w milisekundach. Odczyt **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeOutDuration() override
```

## Uwagi


Przykład: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Dodaj ramkę audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Ustaw czas trwania końcowego wyciszenia na 500 ms
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Klasa [AudioFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)