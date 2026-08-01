---
title: get_TrimFromStart()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert de tijdsduur die aan het begin van de media moet worden verwijderd tijdens het afspelen, in milliseconden. Alleen-lezen float.
type: docs
weight: 404
url: /nl/aspose.slides/audioframe/get_trimfromstart/
---
## AudioFrame::get_TrimFromStart() methode


Specificeert de tijdsduur die aan het begin van de media moet worden verwijderd tijdens het afspelen, in milliseconden. Alleen-lezen **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromStart() override
```

## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Voeg audioframe toe
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Stel de starttrimtijd in op 1,5 seconden
audioFrame->set_TrimFromStart(1500.0f);
```

## Zie ook

* Klasse [AudioFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)