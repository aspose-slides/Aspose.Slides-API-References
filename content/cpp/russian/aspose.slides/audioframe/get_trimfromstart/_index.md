---
title: get_TrimFromStart()
second_title: Aspose.Slides для C++ справочник API
description: Указывает продолжительность времени, которую следует удалить из начала медиа при воспроизведении, в миллисекундах. Читает float.
type: docs
weight: 404
url: /ru/aspose.slides/audioframe/get_trimfromstart/
---
## AudioFrame::get_TrimFromStart() метод


Указывает продолжительность времени, которую следует удалить из начала медиа во время воспроизведения, в миллисекундах. Читает **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromStart() override
```

## Примечания


Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Добавить аудио-кадр
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Установить время начала обрезки 1,5 секунды
audioFrame->set_TrimFromStart(1500.0f);
```

## См. также

* Класс [AudioFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)