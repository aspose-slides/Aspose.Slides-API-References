---
title: set_TrimFromStart()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica la durata temporale da rimuovere dall'inizio del media durante la riproduzione, in millisecondi. Scrivi float.
type: docs
weight: 417
url: /it/aspose.slides/iaudioframe/set_trimfromstart/
---
## IAudioFrame::set_TrimFromStart(float) metodo


Specifica la durata temporale da rimuovere dall'inizio del media durante la riproduzione, in millisecondi. Scrivi **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromStart(float value)=0
```

## Osservazioni


Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Aggiungi Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Imposta il tempo di ritaglio iniziale a 1.5 secondi
audioFrame->set_TrimFromStart(1500.0f);
```

## Vedi anche

* Classe [IAudioFrame](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)