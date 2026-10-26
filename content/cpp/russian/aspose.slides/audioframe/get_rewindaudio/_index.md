---
title: get_RewindAudio()
second_title: Aspose.Slides для C++ справка API
description: Определяет, будет ли аудио автоматически перематываться к началу после воспроизведения. Только для чтения bool.
type: docs
weight: 235
url: /ru/aspose.slides/audioframe/get_rewindaudio/
---
## AudioFrame::get_RewindAudio() метод


Определяет, будет ли аудио автоматически перематываться к началу после воспроизведения. Только для чтения **bool**.

```cpp
bool Aspose::Slides::AudioFrame::get_RewindAudio() override
```

## Примечания



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Добавить аудиофрейм
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Установить воспроизведение аудио на всех слайдах
audioFrame->set_PlayAcrossSlides(true);

// Установить автоматический возврат аудио к началу после воспроизведения
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## См. также

* Класс [AudioFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)