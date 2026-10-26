---
title: set_TrimFromEnd()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert de tijdsduur die tijdens het afspelen van de media van het einde moet worden verwijderd, in milliseconden. Schrijf float.
type: docs
weight: 443
url: /nl/aspose.slides/audioframe/set_trimfromend/
---
## AudioFrame::set_TrimFromEnd(float) methode


Specificeert de tijdsduur die tijdens het afspelen van de media van het einde moet worden verwijderd, in milliseconden. Schrijf **float**.

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromEnd(float value) override
```

## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Voeg Audio Frame toe
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Stel de eindtrimtijd in op 2 seconden
audioFrame->set_TrimFromEnd(2000.0f);
```

## Zie ook

* Klasse [AudioFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)