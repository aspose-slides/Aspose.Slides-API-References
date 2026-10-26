---
title: get_TrimFromEnd()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert de tijdsduur die aan het einde van de media moet worden verwijderd tijdens het afspelen, in milliseconden. Lezen float.
type: docs
weight: 430
url: /nl/aspose.slides/audioframe/get_trimfromend/
---
## AudioFrame::get_TrimFromEnd() methode

Specificeert de tijdsduur die aan het einde van de media moet worden verwijderd tijdens het afspelen, in milliseconden. Lezen **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromEnd() override
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

* Klasse [AudioFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)