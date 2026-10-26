---
title: get_RewindAudio()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob Audio nach dem Abspielen automatisch zum Start zurückgespult wird. Lesen **bool**.
type: docs
weight: 235
url: /de/aspose.slides/audioframe/get_rewindaudio/
---
## AudioFrame::get_RewindAudio() Methode


Bestimmt, ob Audio nach dem Abspielen automatisch zum Start zurückgespult wird. Lesen **bool**.

```cpp
bool Aspose::Slides::AudioFrame::get_RewindAudio() override
```

## Hinweise



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Audio-Frame hinzufügen
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Audio über die Folien hinweg abspielen
audioFrame->set_PlayAcrossSlides(true);

// Audio so einstellen, dass es nach dem Abspielen automatisch zum Anfang zurückspult
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Siehe auch

* Klasse [AudioFrame](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)