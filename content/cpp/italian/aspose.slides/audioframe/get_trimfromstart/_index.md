---
title: get_TrimFromStart()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica la durata da rimuovere dall'inizio del media durante la riproduzione, in millisecondi. Lettura float.
type: docs
weight: 404
url: /it/aspose.slides/audioframe/get_trimfromstart/
---
## AudioFrame::get_TrimFromStart() metodo

Specifica la durata da rimuovere dall'inizio del media durante la riproduzione, in millisecondi. Lettura **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromStart() override
```

## Osservazioni

Esempio:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Aggiungi fotogramma audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Imposta il tempo di taglio iniziale a 1,5 secondi
audioFrame->set_TrimFromStart(1500.0f);
```

## Vedi anche

* Classe [AudioFrame](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)