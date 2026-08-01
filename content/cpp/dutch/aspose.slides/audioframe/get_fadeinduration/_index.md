---
title: get_FadeInDuration()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert de tijdsduur voor de initiële fade-in van de media in milliseconden. Lezen float.
type: docs
weight: 326
url: /nl/aspose.slides/audioframe/get_fadeinduration/
---
## AudioFrame::get_FadeInDuration() methode


Specificeert de tijdsduur voor de initiële fade-in van de media in milliseconden. Lezen **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeInDuration() override
```

## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Audioframe toevoegen
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Stel de duur van de initiële fade-in in op 200 ms
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Klasse [AudioFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)