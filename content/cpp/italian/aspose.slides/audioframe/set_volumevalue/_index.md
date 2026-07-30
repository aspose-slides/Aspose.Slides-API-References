---
title: set_VolumeValue()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta il volume audio in percentuale. Scrivi float.
type: docs
weight: 391
url: /it/aspose.slides/audioframe/set_volumevalue/
---
## AudioFrame::set_VolumeValue(float) metodo


Imposta il volume audio in percentuale. Scrivi **float**.

```cpp
void Aspose::Slides::AudioFrame::set_VolumeValue(float value) override
```

## Osservazioni


Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Aggiungi Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Imposta la durata della dissolvenza iniziale a 200ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Classe [AudioFrame](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)