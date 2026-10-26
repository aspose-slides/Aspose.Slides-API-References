---
title: get_FadeOutDuration()
second_title: Aspose.Slides per il riferimento API C++
description: Specifica la durata temporale per la dissolvenza finale del media in millisecondi. Leggi float.
type: docs
weight: 352
url: /it/aspose.slides/audioframe/get_fadeoutduration/
---
## AudioFrame::get_FadeOutDuration() metodo

Specifica la durata temporale per la dissolvenza finale del media in millisecondi. Leggi **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeOutDuration() override
```

## Osservazioni

Esempio:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Aggiungi Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Imposta la durata della dissolvenza finale a 500ms
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Classe [AudioFrame](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)