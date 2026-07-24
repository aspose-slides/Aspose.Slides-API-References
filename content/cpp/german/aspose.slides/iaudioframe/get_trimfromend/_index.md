---
title: get_TrimFromEnd()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Zeitdauer an, die beim Abspielen vom Ende des Mediums entfernt werden soll, in Millisekunden. Lesen float.
type: docs
weight: 430
url: /de/aspose.slides/iaudioframe/get_trimfromend/
---
## IAudioFrame::get_TrimFromEnd() Methode


Gibt die Zeitdauer an, die beim Abspielen vom Ende des Mediums entfernt werden soll, in Millisekunden. Lesen **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromEnd()=0
```

## Anmerkungen


Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Audio-Frame hinzufügen
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Endtrimmzeit auf 2 Sekunden setzen
audioFrame->set_TrimFromEnd(2000.0f);
```

## Siehe auch

* Klasse [IAudioFrame](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)