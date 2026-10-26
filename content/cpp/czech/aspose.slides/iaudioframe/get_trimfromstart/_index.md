---
title: get_TrimFromStart()
second_title: Aspose.Slides pro C++ – reference API
description: Určuje časovou délku, která má být během přehrávání odebrána od začátku média, v milisekundách. Čte float.
type: docs
weight: 404
url: /cs/aspose.slides/iaudioframe/get_trimfromstart/
---
## IAudioFrame::get_TrimFromStart() metoda

Určuje časovou délku, která má být během přehrávání odebrána od začátku média, v milisekundách. Čte **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromStart()=0
```

## Poznámky

Příklad:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Přidat zvukový rámec
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Nastavit čas ořezání od začátku na 1,5 sekundy
audioFrame->set_TrimFromStart(1500.0f);
```

## Viz také

* Třída [IAudioFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)