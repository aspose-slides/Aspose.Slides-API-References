---
title: get_TrimFromEnd()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert de tijdsduur die aan het einde van de media moet worden verwijderd tijdens het afspelen, in milliseconden. Lees float.
type: docs
weight: 430
url: /nl/aspose.slides/iaudioframe/get_trimfromend/
---
## IAudioFrame::get_TrimFromEnd() methode

Specificeert de tijdsduur die aan het einde van de media moet worden verwijderd tijdens afspelen, in milliseconden. Lees **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromEnd()=0
```

## Opmerkingen

Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Voeg audioframe toe
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Stel de eindtrimtijd in op 2 seconden
audioFrame->set_TrimFromEnd(2000.0f);
```

## Zie ook

* Klasse [IAudioFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)