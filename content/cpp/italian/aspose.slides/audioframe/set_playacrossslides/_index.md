---
title: set_PlayAcrossSlides()
second_title: Riferimento API di Aspose.Slides per C++
description: Determina se l'audio viene riprodotto durante le diapositive. Scrivi bool.
type: docs
weight: 222
url: /it/aspose.slides/audioframe/set_playacrossslides/
---
## AudioFrame::set_PlayAcrossSlides(bool) metodo


Determina se l'audio viene riprodotto durante le diapositive. Scrivi **bool**.

```cpp
void Aspose::Slides::AudioFrame::set_PlayAcrossSlides(bool value) override
```

## Osservazioni



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Aggiungi fotogramma audio
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Imposta l'audio per riprodursi durante le diapositive
audioFrame->set_PlayAcrossSlides(true);

// Imposta l'audio per riavvolgere automaticamente all'inizio dopo la riproduzione
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Vedi anche

* Classe [AudioFrame](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)