---
title: set_VolumeValue()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Ustawia głośność dźwięku w procentach. Zapisz float.
type: docs
weight: 391
url: /pl/aspose.slides/audioframe/set_volumevalue/
---
## AudioFrame::set_VolumeValue(float) metoda

Ustawia głośność dźwięku w procentach. Zapisz **float**.

```cpp
void Aspose::Slides::AudioFrame::set_VolumeValue(float value) override
```

## Uwagi

Przykład:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Dodaj ramkę audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Ustaw czas trwania początkowego przyciemnienia na 200 ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Klasa [AudioFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)