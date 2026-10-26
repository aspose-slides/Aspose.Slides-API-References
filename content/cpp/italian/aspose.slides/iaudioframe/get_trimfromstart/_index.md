---
title: get_TrimFromStart()
second_title: Riferimento API di Aspose.Slides per C++ 
description: Specifica la durata di tempo da rimuovere dall'inizio del supporto durante la riproduzione, in millisecondi. Leggi float.
type: docs
weight: 404
url: /it/aspose.slides/iaudioframe/get_trimfromstart/
---
## IAudioFrame::get_TrimFromStart() metodo


Specifica la durata di tempo da rimuovere dall'inizio del supporto durante la riproduzione, in millisecondi. Leggi **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromStart()=0
```

## Note


Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Aggiungi fotogramma audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Imposta il tempo di ritaglio iniziale a 1,5 secondi
audioFrame->set_TrimFromStart(1500.0f);
```

## Vedi anche

* Classe [IAudioFrame](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)