---
title: set_TrimFromStart()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Určuje časové období, které má být během přehrávání odstraněno ze začátku média, v milisekundách. Zapište float.
type: docs
weight: 417
url: /cs/aspose.slides/iaudioframe/set_trimfromstart/
---
## IAudioFrame::set_TrimFromStart(float) metoda

Určuje časové období, které má být během přehrávání odstraněno ze začátku média, v milisekundách. Zapište **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromStart(float value)=0
```

## Poznámky

Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Přidat audio snímek
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Nastavit čas ořezu od začátku 1,5 sekundy
audioFrame->set_TrimFromStart(1500.0f);
```

## Viz také

* Třída [IAudioFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)