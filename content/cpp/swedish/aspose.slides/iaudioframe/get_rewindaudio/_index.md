---
title: get_RewindAudio()
second_title: Aspose.Slides för C++ API-referens
description: Avgör om ett ljud automatiskt spolas tillbaka till början efter uppspelning. Läs bool.
type: docs
weight: 235
url: /sv/aspose.slides/iaudioframe/get_rewindaudio/
---
## IAudioFrame::get_RewindAudio() metod


Avgör om ett ljud automatiskt spolas tillbaka till början efter uppspelning. Läs **bool**.

```cpp
virtual bool Aspose::Slides::IAudioFrame::get_RewindAudio()=0
```

## Anmärkningar



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Lägg till ljudram
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Ställ in att ljudet spelas på alla bilder
audioFrame->set_PlayAcrossSlides(true);

// Ställ in att ljudet automatiskt spolas tillbaka till början efter uppspelning
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## Se även

* Klass [IAudioFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)