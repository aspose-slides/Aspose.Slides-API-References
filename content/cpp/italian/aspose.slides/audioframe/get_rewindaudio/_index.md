---
title: get_RewindAudio()
second_title: Riferimento API Aspose.Slides per C++
description: Determina se l'audio viene automaticamente riavvolto all'inizio dopo la riproduzione. Leggi bool.
type: docs
weight: 235
url: /it/aspose.slides/audioframe/get_rewindaudio/
---
## AudioFrame::get_RewindAudio() metodo

Determina se l'audio viene automaticamente riportato all'inizio dopo la riproduzione. Leggi **bool**.

```cpp
bool Aspose::Slides::AudioFrame::get_RewindAudio() override
```

## Osservazioni



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Add Audio Frame
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
* Library [Aspose.Slides](../../../)