---
title: set_VolumeValue()
second_title: Aspose.Slides voor C++ API Referentie
description: Stelt het audio volume in procenten in. Schrijf float.
type: docs
weight: 391
url: /nl/aspose.slides/iaudioframe/set_volumevalue/
---
## IAudioFrame::set_VolumeValue(float) methode


Stelt het audio volume in procenten in. Schrijf **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_VolumeValue(float value)=0
```

## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Voeg een audiokader toe
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the duration of the starting fade for 200ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Klasse [IAudioFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)