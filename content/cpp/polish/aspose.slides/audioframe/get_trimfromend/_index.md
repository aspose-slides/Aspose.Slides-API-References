---
title: get_TrimFromEnd()
second_title: Aspose.Slides dla C++ – referencja API
description: Określa czas trwania, który ma zostać usunięty z końca mediów podczas odtwarzania, w milisekundach. Odczyt float.
type: docs
weight: 430
url: /pl/aspose.slides/audioframe/get_trimfromend/
---
## AudioFrame::get_TrimFromEnd() metoda


Określa czas trwania, który ma zostać usunięty z końca multimediów podczas odtwarzania, w milisekundach. Odczyt **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromEnd() override
```

## Uwagi


Przykład: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Dodaj ramkę audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Ustaw czas przycinania od końca na 2 sekundy
audioFrame->set_TrimFromEnd(2000.0f);
```

## Zobacz także

* Klasa [AudioFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)