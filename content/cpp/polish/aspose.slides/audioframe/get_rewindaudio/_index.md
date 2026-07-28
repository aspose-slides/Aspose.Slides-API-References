---
title: get_RewindAudio()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Określa, czy audio jest automatycznie przewijane do początku po odtworzeniu. Odczyt bool.
type: docs
weight: 235
url: /pl/aspose.slides/audioframe/get_rewindaudio/
---
## AudioFrame::get_RewindAudio() metoda


Określa, czy audio jest automatycznie przewijane do początku po odtworzeniu. Odczyt **bool**.

```cpp
bool Aspose::Slides::AudioFrame::get_RewindAudio() override
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

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Zobacz także

* Klasa [AudioFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)