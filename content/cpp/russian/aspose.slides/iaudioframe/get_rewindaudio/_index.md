---
title: get_RewindAudio()
second_title: Справочник API Aspose.Slides для C++
description: Определяет, будет ли аудио автоматически перематываться к началу после воспроизведения. Читает bool.
type: docs
weight: 235
url: /ru/aspose.slides/iaudioframe/get_rewindaudio/
---
## IAudioFrame::get_RewindAudio() метод


Определяет, будет ли аудио автоматически перематываться к началу после воспроизведения. Читает **bool**.

```cpp
virtual bool Aspose::Slides::IAudioFrame::get_RewindAudio()=0
```

## Примечания



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Добавить аудио-кадр
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Установить воспроизведение аудио на всех слайдах
audioFrame->set_PlayAcrossSlides(true);

// Установить автоматическую перемотку аудио к началу после воспроизведения
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## См. также

* Класс [IAudioFrame](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)