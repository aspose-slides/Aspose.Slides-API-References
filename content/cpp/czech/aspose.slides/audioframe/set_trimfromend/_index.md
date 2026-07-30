---
title: set_TrimFromEnd()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Určuje časovou délku, která má být během přehrávání odebrána od konce média, v milisekundách. Zapište float.
type: docs
weight: 443
url: /cs/aspose.slides/audioframe/set_trimfromend/
---
## AudioFrame::set_TrimFromEnd(float) metoda


Určuje časovou délku, která má být během přehrávání odebrána od konce média, v milisekundách. Zapište **float**.

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromEnd(float value) override
```

## Poznámky


Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Přidat audio rámec
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Nastavit čas oříznutí z konce na 2 sekundy
audioFrame->set_TrimFromEnd(2000.0f);
```

## Viz také

* Třída [AudioFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)