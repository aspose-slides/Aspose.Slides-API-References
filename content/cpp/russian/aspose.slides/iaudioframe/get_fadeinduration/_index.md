---
title: get_FadeInDuration()
second_title: Справочник API Aspose.Slides для C++
description: Указывает продолжительность времени для начального плавного появления медиа в миллисекундах. Читается float.
type: docs
weight: 326
url: /ru/aspose.slides/iaudioframe/get_fadeinduration/
---
## IAudioFrame::get_FadeInDuration() метод

Указывает продолжительность времени для начального плавного появления медиа в миллисекундах. Читается **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_FadeInDuration()=0
```

## Примечания

Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Добавить аудио кадр
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Установить длительность начального затухания на 200 мс
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## См. также

* Класс [IAudioFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)