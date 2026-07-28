---
title: get_FadeInDuration()
second_title: Aspose.Slides dla C++ - Referencja API
description: Określa czas trwania początkowego efektu fade-in multimediów w milisekundach. Odczyt float.
type: docs
weight: 326
url: /pl/aspose.slides/iaudioframe/get_fadeinduration/
---
## IAudioFrame::get_FadeInDuration() metoda

Określa czas trwania początkowego fade-in multimediów w milisekundach. Odczyt **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_FadeInDuration()=0
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

* Klasa [IAudioFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)