---
title: get_TrimFromEnd()
second_title: Aspose.Slides pro C++ API Reference
description: Specifikuje časovou dobu, která má být během přehrávání odebrána z konce média, v milisekundách. Čte float.
type: docs
weight: 430
url: /cs/aspose.slides/iaudioframe/get_trimfromend/
---
## IAudioFrame::get_TrimFromEnd() metoda


Specifikuje časovou dobu, která má být během přehrávání odebrána z konce média, v milisekundách. Čte **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromEnd()=0
```

## Poznámky


Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Přidat audio rámec
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Nastavit čas ořezu na konci na 2 sekundy
audioFrame->set_TrimFromEnd(2000.0f);
```

## Viz také

* Třída [IAudioFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)