---
title: get_FadeOutDuration()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Zeitdauer für das abschließende Ausblenden des Mediums in Millisekunden an. Lesen float.
type: docs
weight: 352
url: /de/aspose.slides/iaudioframe/get_fadeoutduration/
---
## IAudioFrame::get_FadeOutDuration() Methode

Gibt die Zeitdauer für das abschließende Ausblenden des Mediums in Millisekunden an. Lesen **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_FadeOutDuration()=0
```

## Bemerkungen

Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Audio-Frame hinzufügen
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Setze die Dauer des abschließenden Ausblendens auf 500 ms
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Klasse [IAudioFrame](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)