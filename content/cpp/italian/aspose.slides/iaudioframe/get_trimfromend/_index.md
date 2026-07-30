---
title: get_TrimFromEnd()
second_title: Aspose.Slides per C++ Riferimento API
description: Specifica la durata temporale da rimuovere dalla fine del media durante la riproduzione, in millisecondi. Leggi float.
type: docs
weight: 430
url: /it/aspose.slides/iaudioframe/get_trimfromend/
---
## IAudioFrame::get_TrimFromEnd() metodo


Specifica la durata temporale da rimuovere dalla fine del media durante la riproduzione, in millisecondi. Leggi **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromEnd()=0
```

## Osservazioni


Esempio:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Aggiungi frame audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Imposta il tempo di taglio finale a 2 secondi
audioFrame->set_TrimFromEnd(2000.0f);
```

## Vedi anche

* Classe [IAudioFrame](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)