---
title: get_TrimFromStart()
second_title: Aspose.Slides pro C++ referenci API
description: Určuje časovou dobu, která má být během přehrávání odebrána od začátku média, v milisekundách. Číst float.
type: docs
weight: 404
url: /cs/aspose.slides/audioframe/get_trimfromstart/
---
## AudioFrame::get_TrimFromStart() metoda


Určuje časovou dobu, která má být během přehrávání odebrána od začátku média, v milisekundách. Číst **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromStart() override
```

## Poznámky


Příklad:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Přidat audio rámec
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Nastavit čas ořezu od začátku 1,5 sekundy
audioFrame->set_TrimFromStart(1500.0f);
```

## Viz také

* Třída [AudioFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)