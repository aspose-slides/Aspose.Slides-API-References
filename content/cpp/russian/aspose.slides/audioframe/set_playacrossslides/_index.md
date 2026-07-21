---
title: set_PlayAcrossSlides()
second_title: Aspose.Slides для C++ справочник API
description: Определяет, воспроизводится ли аудио на всех слайдах. Записывает bool.
type: docs
weight: 222
url: /ru/aspose.slides/audioframe/set_playacrossslides/
---
## AudioFrame::set_PlayAcrossSlides(bool) метод


Определяет, воспроизводится ли аудио на всех слайдах. Записывает **bool**.

```cpp
void Aspose::Slides::AudioFrame::set_PlayAcrossSlides(bool value) override
```

## Примечания



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Добавить аудио-кадр
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