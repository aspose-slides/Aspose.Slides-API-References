---
title: get_PlayAcrossSlides()
second_title: Aspose.Slides для справочника API C++
description: Определяет, воспроизводится ли аудио на всех слайдах. Чтение bool.
type: docs
weight: 209
url: /ru/aspose.slides/audioframe/get_playacrossslides/
---
## AudioFrame::get_PlayAcrossSlides() метод

Определяет, воспроизводится ли аудио на всех слайдах. Чтение **bool**.

```cpp
bool Aspose::Slides::AudioFrame::get_PlayAcrossSlides() override
```

## Примечания



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Add Audio Frame
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Set Audio to play across the slides
audioFrame->set_PlayAcrossSlides(true);

// Set Audio to automatically rewind to start after playing
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## См. также

* Класс [AudioFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)