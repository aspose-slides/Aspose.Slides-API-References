---
title: set_FadeInDuration()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert de tijdsduur voor de initiële fade-in van de media in milliseconden. Schrijf float.
type: docs
weight: 339
url: /nl/aspose.slides/audioframe/set_fadeinduration/
---
## AudioFrame::set_FadeInDuration(float) methode


Specificeert de tijdsduur voor de initiële fade-in van de media in milliseconden. Schrijf **float**.

```cpp
void Aspose::Slides::AudioFrame::set_FadeInDuration(float value) override
```

## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Voeg een audiokader toe
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Stel de duur van de start-fade in op 200 ms
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Klasse [AudioFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)