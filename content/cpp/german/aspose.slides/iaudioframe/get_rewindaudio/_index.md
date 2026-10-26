---
title: get_RewindAudio()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob ein Audio nach dem Abspielen automatisch zum Anfang zurückgespult wird. Lese bool.
type: docs
weight: 235
url: /de/aspose.slides/iaudioframe/get_rewindaudio/
---
## IAudioFrame::get_RewindAudio() Methode


Bestimmt, ob ein Audio nach dem Abspielen automatisch zum Anfang zurückgespult wird. Lese **bool**.

```cpp
virtual bool Aspose::Slides::IAudioFrame::get_RewindAudio()=0
```

## Anmerkungen



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Audio-Frame hinzufügen
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Audio über alle Folien abspielen
audioFrame->set_PlayAcrossSlides(true);

// Audio nach dem Abspielen automatisch zum Anfang zurückspulen
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## Siehe auch

* Klasse [IAudioFrame](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)