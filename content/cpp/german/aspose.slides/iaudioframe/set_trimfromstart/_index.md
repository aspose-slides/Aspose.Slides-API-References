---
title: set_TrimFromStart()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Zeitdauer an, die zu Beginn der Medien während der Wiedergabe entfernt werden soll, in Millisekunden. Schreiben Sie float.
type: docs
weight: 417
url: /de/aspose.slides/iaudioframe/set_trimfromstart/
---
## IAudioFrame::set_TrimFromStart(float) Methode


Gibt die Zeitdauer an, die zu Beginn der Medien während der Wiedergabe entfernt werden soll, in Millisekunden. Schreiben Sie **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromStart(float value)=0
```

## Hinweise


Beispiel:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Audio-Frame hinzufügen
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Setzt die Start-Trimmzeit auf 1,5 Sekunden
audioFrame->set_TrimFromStart(1500.0f);
```

## Siehe auch

* Klasse [IAudioFrame](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)