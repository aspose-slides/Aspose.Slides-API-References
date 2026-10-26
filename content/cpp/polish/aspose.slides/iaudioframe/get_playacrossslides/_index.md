---
title: get_PlayAcrossSlides()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Określa, czy dźwięk jest odtwarzany na wszystkich slajdach. Odczyt bool.
type: docs
weight: 209
url: /pl/aspose.slides/iaudioframe/get_playacrossslides/
---
## IAudioFrame::get_PlayAcrossSlides() metoda


Określa, czy dźwięk jest odtwarzany na wszystkich slajdach. Odczyt **bool**.

```cpp
virtual bool Aspose::Slides::IAudioFrame::get_PlayAcrossSlides()=0
```

## Uwagi



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Dodaj ramkę audio
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Ustaw audio, aby odtwarzało się na wszystkich slajdach
audioFrame->set_PlayAcrossSlides(true);

// Ustaw audio, aby automatycznie przewijało się do początku po odtworzeniu
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## Zobacz także

* Klasa [IAudioFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)