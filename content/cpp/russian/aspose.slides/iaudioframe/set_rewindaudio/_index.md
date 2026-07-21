---
title: set_RewindAudio()
second_title: Aspose.Slides для справочника API C++
description: Определяет, будет ли аудио автоматически перематываться к началу после воспроизведения. Записывает bool.
type: docs
weight: 248
url: /ru/aspose.slides/iaudioframe/set_rewindaudio/
---
## IAudioFrame::set_RewindAudio(bool) метод

Определяет, будет ли аудио автоматически перемотываться к началу после воспроизведения. Записывает **bool**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_RewindAudio(bool value)=0
```

## Замечания


```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Добавить аудио кадр
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Установить воспроизведение аудио на всех слайдах
audioFrame->set_PlayAcrossSlides(true);

// Установить автоматическую перемотку аудио к началу после воспроизведения
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```


## См. также

* Класс [IAudioFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)