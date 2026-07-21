---
title: get_FadeOutDuration()
second_title: Справочник API Aspose.Slides для C++
description: Указывает продолжительность времени для завершающего затухания медиа в миллисекундах. Читает float.
type: docs
weight: 352
url: /ru/aspose.slides/audioframe/get_fadeoutduration/
---
## AudioFrame::get_FadeOutDuration() метод


Указывает продолжительность времени для завершающего затухания медиа в миллисекундах. Читает **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeOutDuration() override
```

## Примечания


Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Добавить аудио-кадр
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Установить длительность конечного затухания на 500 мс
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Смотрите также

* Класс [AudioFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)