---
title: get_VolumeValue()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert het audio-volume in procenten. Leest float.
type: docs
weight: 378
url: /nl/aspose.slides/iaudioframe/get_volumevalue/
---
## IAudioFrame::get_VolumeValue() methode


Retourneert het audio-volume in procenten. Leest **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_VolumeValue()=0
```

## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Voeg audioframe toe
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Stel de duur van de start fade in op 200ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Klasse [IAudioFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)