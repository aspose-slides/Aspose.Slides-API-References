---
title: get_FadeInDuration()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Zeitdauer für das anfängliche Einblenden des Mediums in Millisekunden an. Lesen float.
type: docs
weight: 326
url: /de/aspose.slides/audioframe/get_fadeinduration/
---
## AudioFrame::get_FadeInDuration() Methode

Gibt die Zeitdauer für das anfängliche Einblenden des Mediums in Millisekunden an. Lesen **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeInDuration() override
```

## Hinweise

Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Audio-Frame hinzufügen
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Dauer des Start-Fades auf 200ms festlegen
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Klasse [AudioFrame](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)