---
title: set_VolumeValue()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt het audiovolume in procenten in. Schrijf float.
type: docs
weight: 391
url: /nl/aspose.slides/audioframe/set_volumevalue/
---
## AudioFrame::set_VolumeValue(float) methode


Stelt het audiovolume in procenten in. Schrijf **float**.

```cpp
void Aspose::Slides::AudioFrame::set_VolumeValue(float value) override
```

## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Voeg audioframe toe
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Stel de duur van de startfading in op 200 ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Klasse [AudioFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)