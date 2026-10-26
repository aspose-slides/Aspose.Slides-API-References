---
title: set_TrimFromEnd()
second_title: Aspose.Slides pro C++ - reference API
description: Určuje časovou délku, která má být během přehrávání odebrána od konce média, v milisekundách. Zapište float.
type: docs
weight: 443
url: /cs/aspose.slides/iaudioframe/set_trimfromend/
---
## IAudioFrame::set_TrimFromEnd(float) metoda


Určuje časovou délku, která má být během přehrávání odebrána od konce média, v milisekundách. Zapište **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromEnd(float value)=0
```

## Poznámky


Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Přidat zvukový rámec
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Nastavit čas oříznutí na konci na 2 sekundy
audioFrame->set_TrimFromEnd(2000.0f);
```

## Viz také

* Třída [IAudioFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)