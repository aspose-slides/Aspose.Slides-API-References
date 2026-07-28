---
title: get_TrimFromStart()
second_title: Aspose.Slides for C++ – odniesienie do API
description: Określa czas trwania, który ma zostać usunięty z początku mediów podczas odtwarzania, w milisekundach. Odczyt float.
type: docs
weight: 404
url: /pl/aspose.slides/audioframe/get_trimfromstart/
---
## AudioFrame::get_TrimFromStart() metoda

Określa czas trwania, który ma zostać usunięty z początku mediów podczas odtwarzania, w milisekundach. Odczyt **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromStart() override
```

## Uwagi

Przykład: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Dodaj ramkę audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the start trimming time 1.5 seconds
audioFrame->set_TrimFromStart(1500.0f);
```

## Zobacz także

* Klasa [AudioFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)