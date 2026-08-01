---
title: set_TrimFromStart()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert de tijdsduur die moet worden verwijderd van het begin van de media tijdens het afspelen, in milliseconden. Schrijf float.
type: docs
weight: 417
url: /nl/aspose.slides/audioframe/set_trimfromstart/
---
## AudioFrame::set_TrimFromStart(float) methode


Specificeert de tijdsduur die moet worden verwijderd van het begin van de media tijdens het afspelen, in milliseconden. Schrijf **float**.

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromStart(float value) override
```

## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Voeg een audioframe toe
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Stel de starttrimtijd in op 1.5 seconden
audioFrame->set_TrimFromStart(1500.0f);
```

## Zie ook

* Klasse [AudioFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)