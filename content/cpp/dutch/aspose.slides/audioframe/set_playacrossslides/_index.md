---
title: set_PlayAcrossSlides()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt of audio over de dia's wordt afgespeeld. Schrijf bool.
type: docs
weight: 222
url: /nl/aspose.slides/audioframe/set_playacrossslides/
---
## AudioFrame::set_PlayAcrossSlides(bool) methode


Bepaalt of audio wordt afgespeeld over de dia's. Schrijf **bool**.

```cpp
void Aspose::Slides::AudioFrame::set_PlayAcrossSlides(bool value) override
```

## Opmerkingen



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Voeg Audio Frame toe
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Stel Audio in om over de dia's af te spelen
audioFrame->set_PlayAcrossSlides(true);

// Stel Audio in om automatisch terug te spoelen naar het begin na het afspelen
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Zie ook

* Klasse [AudioFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)