---
title: set_RewindAudio()
second_title: Riferimento API di Aspose.Slides per C++
description: Determina se l'audio viene automaticamente riavvolto all'inizio dopo la riproduzione. Scrivi bool.
type: docs
weight: 248
url: /it/aspose.slides/audioframe/set_rewindaudio/
---
## AudioFrame::set_RewindAudio(bool) metodo

Determina se l'audio viene automaticamente riavvolto all'inizio dopo la riproduzione. Scrivi **bool**.

```cpp
void Aspose::Slides::AudioFrame::set_RewindAudio(bool value) override
```

## Osservazioni

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Aggiungi fotogramma audio
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Set Audio to play across the slides
audioFrame->set_PlayAcrossSlides(true);

// Set Audio to automatically rewind to start after playing
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Vedi anche

* Classe [AudioFrame](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)