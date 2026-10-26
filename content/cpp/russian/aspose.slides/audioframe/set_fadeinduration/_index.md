---
title: set_FadeInDuration()
second_title: Aspose.Slides для C++ справочник API
description: Указывает длительность времени начального плавного появления медиа в миллисекундах. Запишите float.
type: docs
weight: 339
url: /ru/aspose.slides/audioframe/set_fadeinduration/
---
## AudioFrame::set_FadeInDuration(float) метод


Указывает длительность времени начального плавного появления медиа в миллисекундах. Запишите **float**.

```cpp
void Aspose::Slides::AudioFrame::set_FadeInDuration(float value) override
```

## Примечания


Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Добавить аудио-кадр
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Установить длительность начального затухания на 200 мс
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## См. также

* Класс [AudioFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)