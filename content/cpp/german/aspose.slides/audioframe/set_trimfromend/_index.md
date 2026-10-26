---
title: set_TrimFromEnd()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Zeitdauer an, die am Ende des Mediums während der Wiedergabe entfernt werden soll, in Millisekunden. Schreiben float.
type: docs
weight: 443
url: /de/aspose.slides/audioframe/set_trimfromend/
---
## AudioFrame::set_TrimFromEnd(float) Methode


Gibt die Zeitdauer an, die am Ende des Mediums während der Wiedergabe entfernt werden soll, in Millisekunden. Schreiben **float**.

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromEnd(float value) override
```

## Hinweise


Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Audio-Frame hinzufügen
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Setzt die Endtrimmszeit auf 2 Sekunden
audioFrame->set_TrimFromEnd(2000.0f);
```

## Siehe auch

* Klasse [AudioFrame](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)