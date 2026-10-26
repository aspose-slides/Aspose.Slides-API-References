---
title: get_PlayAcrossSlides()
second_title: Riferimento API di Aspose.Slides per C++
description: Determina se un audio viene riprodotto attraverso le diapositive. Solo lettura bool.
type: docs
weight: 209
url: /it/aspose.slides/iaudioframe/get_playacrossslides/
---
## IAudioFrame::get_PlayAcrossSlides() metodo


Determina se un audio viene riprodotto attraverso le diapositive. Solo lettura **bool**.

```cpp
virtual bool Aspose::Slides::IAudioFrame::get_PlayAcrossSlides()=0
```

## Osservazioni



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Aggiungi frame audio
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Imposta l'audio per riprodursi su più diapositive
audioFrame->set_PlayAcrossSlides(true);

// Imposta l'audio per riavvolgere automaticamente all'inizio dopo la riproduzione
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## Vedi anche

* Classe [IAudioFrame](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)