---
title: set_TrimFromEnd()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Określa czas trwania, który ma zostać usunięty z końca mediów podczas odtwarzania, w milisekundach. Zapisz float.
type: docs
weight: 443
url: /pl/aspose.slides/iaudioframe/set_trimfromend/
---
## IAudioFrame::set_TrimFromEnd(float) metoda


Określa czas trwania, który ma zostać usunięty z końca mediów podczas odtwarzania, w milisekundach. Zapisz **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromEnd(float value)=0
```

## Uwagi


Przykład: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Dodaj ramkę audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Ustaw czas przycięcia od końca na 2 sekundy
audioFrame->set_TrimFromEnd(2000.0f);
```

## Zobacz także

* Klasa [IAudioFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)