---
title: set_PlayAcrossSlides()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob Audio über die Folien hinweg abgespielt wird. Schreiben bool.
type: docs
weight: 222
url: /de/aspose.slides/audioframe/set_playacrossslides/
---
## AudioFrame::set_PlayAcrossSlides(bool) Methode


Bestimmt, ob Audio über die Folien hinweg abgespielt wird. Schreiben **bool**.

```cpp
void Aspose::Slides::AudioFrame::set_PlayAcrossSlides(bool value) override
```

## Anmerkungen



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Audio-Frame hinzufügen
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Audio über die Folien hinweg abspielen
audioFrame->set_PlayAcrossSlides(true);

// Audio nach dem Abspielen automatisch zum Anfang zurückspulen
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Siehe auch

* Klasse [AudioFrame](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)