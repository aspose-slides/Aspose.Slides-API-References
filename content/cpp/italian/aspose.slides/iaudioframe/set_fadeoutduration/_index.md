---
title: set_FadeOutDuration()
second_title: Riferimento API Aspose.Slides per C++
description: Specifica la durata temporale per il fade-out finale del media in millisecondi. Scrivi float.
type: docs
weight: 365
url: /it/aspose.slides/iaudioframe/set_fadeoutduration/
---
## IAudioFrame::set_FadeOutDuration(float) metodo


Specifica la durata temporale per il fade-out finale del media in millisecondi. Scrivi **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_FadeOutDuration(float value)=0
```

## Osservazioni


Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Aggiungi fotogramma audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Imposta la durata del fade finale a 500 ms
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Classe [IAudioFrame](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)