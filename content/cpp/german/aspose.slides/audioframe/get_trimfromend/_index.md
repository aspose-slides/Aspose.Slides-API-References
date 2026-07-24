---
title: get_TrimFromEnd()
second_title: Aspose.Slides für C++ API Referenz
description: Gibt die Zeitdauer an, die am Ende des Mediums während der Wiedergabe entfernt werden soll, in Millisekunden. Lesen float.
type: docs
weight: 430
url: /de/aspose.slides/audioframe/get_trimfromend/
---
## AudioFrame::get_TrimFromEnd() Methode

Gibt die Zeitdauer an, die am Ende des Mediums während der Wiedergabe entfernt werden soll, in Millisekunden. Lesen **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromEnd() override
```

## Hinweise

Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Audio-Frame hinzufügen
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Setze die Endabschneidezeit auf 2 Sekunden
audioFrame->set_TrimFromEnd(2000.0f);
```

## Siehe auch

* Klasse [AudioFrame](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)