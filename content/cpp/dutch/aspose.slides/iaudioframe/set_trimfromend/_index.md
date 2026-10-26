---
title: set_TrimFromEnd()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert de tijdsduur die tijdens het afspelen van de media van het einde moet worden verwijderd, in milliseconden. Schrijf float.
type: docs
weight: 443
url: /nl/aspose.slides/iaudioframe/set_trimfromend/
---
## IAudioFrame::set_TrimFromEnd(float) methode


Specificeert de tijdsduur die van het einde van de media moet worden verwijderd tijdens het afspelen, in milliseconden. Schrijf **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromEnd(float value)=0
```

## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Audioframe toevoegen
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Stel de eindtrimtijd in op 2 seconden
audioFrame->set_TrimFromEnd(2000.0f);
```

## Zie ook

* Klasse [IAudioFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)