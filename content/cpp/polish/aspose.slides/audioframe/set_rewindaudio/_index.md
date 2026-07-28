---
title: set_RewindAudio()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Określa, czy audio jest automatycznie przewijane do początku po odtworzeniu. Zapisz bool.
type: docs
weight: 248
url: /pl/aspose.slides/audioframe/set_rewindaudio/
---
## AudioFrame::set_RewindAudio(bool) metoda


Określa, czy audio jest automatycznie przewijane do początku po odtworzeniu. Zapisz **bool**.

```cpp
void Aspose::Slides::AudioFrame::set_RewindAudio(bool value) override
```

## Uwagi



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Dodaj ramkę dźwiękową
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Ustaw audio, aby odtwarzane było we wszystkich slajdach
audioFrame->set_PlayAcrossSlides(true);

// Ustaw audio, aby po odtworzeniu automatycznie przewijało się do początku
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Zobacz także

* Klasa [AudioFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)