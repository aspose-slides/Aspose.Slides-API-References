---
title: get_RewindAudio()
second_title: Riferimento API Aspose.Slides per C++
description: Determina se un audio viene automaticamente riportato all'inizio dopo la riproduzione. Leggi bool.
type: docs
weight: 235
url: /it/aspose.slides/iaudioframe/get_rewindaudio/
---
## IAudioFrame::get_RewindAudio() metodo


Determina se un audio viene automaticamente riportato all'inizio dopo la riproduzione. Leggi **bool**.

```cpp
virtual bool Aspose::Slides::IAudioFrame::get_RewindAudio()=0
```

## Osservazioni



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Aggiungi frame audio
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Imposta l'audio per riprodursi in tutte le diapositive
audioFrame->set_PlayAcrossSlides(true);

// Imposta l'audio per tornare automaticamente all'inizio dopo la riproduzione
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## Vedi anche

* Classe [IAudioFrame](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)