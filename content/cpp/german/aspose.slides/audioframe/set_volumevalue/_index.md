---
title: set_VolumeValue()
second_title: Aspose.Slides für C++ API-Referenz
description: Setzt die Audio-Lautstärke in Prozent. Schreiben Sie float.
type: docs
weight: 391
url: /de/aspose.slides/audioframe/set_volumevalue/
---
## AudioFrame::set_VolumeValue(float) Methode

Setzt die Audio-Lautstärke in Prozent. Schreibe **float**.

```cpp
void Aspose::Slides::AudioFrame::set_VolumeValue(float value) override
```

## Hinweise

Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Audio-Frame hinzufügen
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Setze die Dauer des Start-Fades auf 200 ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Klasse [AudioFrame](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)