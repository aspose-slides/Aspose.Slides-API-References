---
title: set_TrimFromStart()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Zeitdauer an, die zu Beginn des Mediums während der Wiedergabe entfernt werden soll, in Millisekunden. Schreiben float.
type: docs
weight: 417
url: /de/aspose.slides/audioframe/set_trimfromstart/
---
## AudioFrame::set_TrimFromStart(float) Methode

Gibt die Zeitdauer an, die zu Beginn des Mediums während der Wiedergabe entfernt werden soll, in Millisekunden. Schreiben **float**.

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromStart(float value) override
```

## Hinweise

Beispiel:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Audio-Frame hinzufügen
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Setze die Start-Trimmzeit auf 1,5 Sekunden
audioFrame->set_TrimFromStart(1500.0f);
```

## Siehe auch

* Klasse [AudioFrame](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)