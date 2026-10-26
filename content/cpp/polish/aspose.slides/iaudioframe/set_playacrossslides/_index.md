---
title: set_PlayAcrossSlides()
second_title: Aspose.Slides dla C++ – Referencja API
description: Określa, czy dźwięk odtwarzany jest na wszystkich slajdach. Zapisz bool.
type: docs
weight: 222
url: /pl/aspose.slides/iaudioframe/set_playacrossslides/
---
## IAudioFrame::set_PlayAcrossSlides(bool) metoda


Określa, czy audio odtwarzane jest na wszystkich slajdach. Zapisz **bool**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_PlayAcrossSlides(bool value)=0
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