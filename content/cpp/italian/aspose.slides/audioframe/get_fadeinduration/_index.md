---
title: get_FadeInDuration()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica la durata temporale per il fade-in iniziale dei media in millisecondi. Leggi float.
type: docs
weight: 326
url: /it/aspose.slides/audioframe/get_fadeinduration/
---
## AudioFrame::get_FadeInDuration() metodo


Specifica la durata temporale per l'effetto fade-in iniziale dei media in millisecondi. Leggi **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeInDuration() override
```

## Osservazioni


Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Aggiungi Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Imposta la durata del fade iniziale a 200ms
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Classe [AudioFrame](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)