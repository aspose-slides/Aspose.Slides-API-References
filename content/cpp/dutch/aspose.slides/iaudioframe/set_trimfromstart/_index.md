---
title: set_TrimFromStart()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert de tijdsduur die uit het begin van de media moet worden verwijderd tijdens het afspelen, in milliseconden. Schrijf float.
type: docs
weight: 417
url: /nl/aspose.slides/iaudioframe/set_trimfromstart/
---
## IAudioFrame::set_TrimFromStart(float) methode


Specificeert de tijdsduur die uit het begin van de media moet worden verwijderd tijdens het afspelen, in milliseconden. Schrijf **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromStart(float value)=0
```

## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Voeg een audioframe toe
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the start trimming time 1.5 seconds
audioFrame->set_TrimFromStart(1500.0f);
```

## Zie ook

* Klasse [IAudioFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)