---
title: set_PlayAcrossSlides()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Określa, czy dźwięk jest odtwarzany na wszystkich slajdach. Zapisz bool.
type: docs
weight: 222
url: /pl/aspose.slides/audioframe/set_playacrossslides/
---
## AudioFrame::set_PlayAcrossSlides(bool) metoda

Określa, czy dźwięk jest odtwarzany na wszystkich slajdach. Zapisz **bool**.

```cpp
void Aspose::Slides::AudioFrame::set_PlayAcrossSlides(bool value) override
```

## Uwagi



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Dodaj ramkę audio
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Ustaw audio, aby odtwarzało się na wszystkich slajdach
audioFrame->set_PlayAcrossSlides(true);

// Ustaw audio, aby po odtworzeniu automatycznie przewijało się do początku
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Zobacz także

* Klasa [AudioFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)