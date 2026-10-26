---
title: get_VolumeValue()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert het audiovolume in procenten. Leest float.
type: docs
weight: 378
url: /nl/aspose.slides/audioframe/get_volumevalue/
---
## AudioFrame::get_VolumeValue() methode


Retourneert het audiovolume in procenten. Leest **float**.

```cpp
float Aspose::Slides::AudioFrame::get_VolumeValue() override
```

## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Voeg audioframe toe
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Stel de duur van de startvervaging in op 200 ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Klasse [AudioFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)