---
title: set_TrimFromStart()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Określa czas trwania, który ma zostać usunięty z początku multimediów podczas odtwarzania, w milisekundach. Zapisz float.
type: docs
weight: 417
url: /pl/aspose.slides/iaudioframe/set_trimfromstart/
---
## IAudioFrame::set_TrimFromStart(float) metoda


Określa czas trwania, który ma być usunięty z początku mediów podczas odtwarzania, w milisekundach. Zapisz **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromStart(float value)=0
```

## Uwagi


Przykład: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Dodaj ramkę audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Ustaw czas przycięcia od początku 1,5 sekundy
audioFrame->set_TrimFromStart(1500.0f);
```

## Zobacz także

* Klasa [IAudioFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)