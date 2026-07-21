---
title: get_FadeInDuration()
second_title: Aspose.Slides для C++ API справочник
description: Указывает продолжительность времени для начального плавного появления медиа в миллисекундах. Читает float.
type: docs
weight: 326
url: /ru/aspose.slides/audioframe/get_fadeinduration/
---
## AudioFrame::get_FadeInDuration() метод

Указывает продолжительность времени для начального плавного появления медиа в миллисекундах. Читает **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeInDuration() override
```

## Примечания

Пример:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Добавить аудио кадр
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Установить продолжительность начального затухания на 200 мс
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## См. также

* Класс [AudioFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)