---
title: set_PlayAcrossSlides()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob ein Audio über die Folien hinweg abgespielt wird. Schreiben **bool**.
type: docs
weight: 222
url: /de/aspose.slides/iaudioframe/set_playacrossslides/
---
## IAudioFrame::set_PlayAcrossSlides(bool) Methode


Bestimmt, ob ein Audio über die Folien hinweg abgespielt wird. Schreiben **bool**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_PlayAcrossSlides(bool value)=0
```

## Bemerkungen



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Audio-Frame hinzufügen
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Audio so einstellen, dass es über die Folien hinweg abgespielt wird
audioFrame->set_PlayAcrossSlides(true);

// Audio so einstellen, dass es nach dem Abspielen automatisch zurückspult
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## Siehe auch

* Klasse [IAudioFrame](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)