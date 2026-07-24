---
title: get_VolumeValue()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Audio-Lautstärke in Prozent zurück. Lese float.
type: docs
weight: 378
url: /de/aspose.slides/iaudioframe/get_volumevalue/
---
## IAudioFrame::get_VolumeValue() Methode


Gibt die Audio-Lautstärke in Prozent zurück. Lesen **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_VolumeValue()=0
```

## Hinweise


Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Audio-Frame hinzufügen
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the duration of the starting fade for 200ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Klasse [IAudioFrame](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)