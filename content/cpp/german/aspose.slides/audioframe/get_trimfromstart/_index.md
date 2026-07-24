---
title: get_TrimFromStart()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Zeitdauer an, die zu Beginn des Mediums während der Wiedergabe in Millisekunden entfernt wird. Lese float.
type: docs
weight: 404
url: /de/aspose.slides/audioframe/get_trimfromstart/
---
## AudioFrame::get_TrimFromStart() Methode


Gibt die Zeitdauer an, die zu Beginn des Mediums während der Wiedergabe entfernt werden soll, in Millisekunden. Lesen **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromStart() override
```

## Bemerkungen


Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Audio-Frame hinzufügen
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Startzeit zum Trimmen auf 1,5 Sekunden setzen
audioFrame->set_TrimFromStart(1500.0f);
```

## Siehe auch

* Klasse [AudioFrame](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)