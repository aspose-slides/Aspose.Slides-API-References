---
title: get_VolumeValue()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce il volume audio in percentuale. Leggi float.
type: docs
weight: 378
url: /it/aspose.slides/audioframe/get_volumevalue/
---
## AudioFrame::get_VolumeValue() metodo


Restituisce il volume audio in percentuale. Leggi **float**.

```cpp
float Aspose::Slides::AudioFrame::get_VolumeValue() override
```

## Osservazioni


Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Aggiungi frame audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Imposta la durata della dissolvenza iniziale a 200 ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Classe [AudioFrame](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)