---
title: get_PlayAcrossSlides()
second_title: Aspose.Slides для справочника API C++
description: Определяет, воспроизводится ли аудио на всех слайдах. Читает bool.
type: docs
weight: 209
url: /ru/aspose.slides/iaudioframe/get_playacrossslides/
---
## IAudioFrame::get_PlayAcrossSlides() метод


Определяет, воспроизводится ли аудио на всех слайдах. Читает **bool**.

```cpp
virtual bool Aspose::Slides::IAudioFrame::get_PlayAcrossSlides()=0
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

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## См. также

* Класс [IAudioFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)