---
title: get_VolumeValue()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Audio-Lautstärke in Prozent zurück. Lese float.
type: docs
weight: 378
url: /de/aspose.slides/audioframe/get_volumevalue/
---
## AudioFrame::get_VolumeValue() Methode


Gibt die Audio-Lautstärke in Prozent zurück. Lese **float**.

```cpp
float Aspose::Slides::AudioFrame::get_VolumeValue() override
```

## Hinweise


Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Audio-Frame hinzufügen
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Setze die Dauer des Startfades auf 200 ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Klasse [AudioFrame](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)