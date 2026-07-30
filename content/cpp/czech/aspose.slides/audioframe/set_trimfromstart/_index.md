---
title: set_TrimFromStart()
second_title: Aspose.Slides pro C++ API Reference
description: Specifikuje časovou délku, která má být během přehrávání odebrána od začátku média, v milisekundách. Zapište float.
type: docs
weight: 417
url: /cs/aspose.slides/audioframe/set_trimfromstart/
---
## AudioFrame::set_TrimFromStart(float) metoda


Specifikuje časovou délku, která má být během přehrávání odebrána od začátku média, v milisekundách. Zapište **float**.

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromStart(float value) override
```

## Poznámky


Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Přidat audio rámec
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Nastavit počáteční čas ořezu 1,5 sekundy
audioFrame->set_TrimFromStart(1500.0f);
```

## Viz také

* Třída [AudioFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)