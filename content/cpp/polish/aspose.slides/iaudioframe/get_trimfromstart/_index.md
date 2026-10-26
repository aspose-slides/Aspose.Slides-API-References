---
title: get_TrimFromStart()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Określa czas trwania, który ma zostać usunięty z początku mediów podczas odtwarzania, w milisekundach. Odczyt float.
type: docs
weight: 404
url: /pl/aspose.slides/iaudioframe/get_trimfromstart/
---
## IAudioFrame::get_TrimFromStart() metoda


Określa czas trwania, który ma zostać usunięty z początku mediów podczas odtwarzania, w milisekundach. Odczyt **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromStart()=0
```

## Uwagi


Przykład: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Dodaj ramkę audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Ustaw czas przycięcia od początku na 1,5 sekundy
audioFrame->set_TrimFromStart(1500.0f);
```

## Zobacz też

* Klasa [IAudioFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)