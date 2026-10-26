---
title: set_TrimFromEnd()
second_title: Riferimento API Aspose.Slides per C++
description: Specifica la durata temporale da rimuovere dalla fine del media durante la riproduzione, in millisecondi. Scrivi float.
type: docs
weight: 443
url: /it/aspose.slides/iaudioframe/set_trimfromend/
---
## IAudioFrame::set_TrimFromEnd(float) metodo

Specifica la durata temporale da rimuovere dalla fine del media durante la riproduzione, in millisecondi. Scrivi **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromEnd(float value)=0
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
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)