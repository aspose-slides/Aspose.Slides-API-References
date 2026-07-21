---
title: set_TrimFromStart()
second_title: Справочник API Aspose.Slides для C++
description: Указывает продолжительность времени, которую необходимо удалить из начала медиа при воспроизведении, в миллисекундах. Запишите float.
type: docs
weight: 417
url: /ru/aspose.slides/audioframe/set_trimfromstart/
---
## AudioFrame::set_TrimFromStart(float) метод


Указывает продолжительность времени, которую нужно удалить из начала медиа при воспроизведении, в миллисекундах. Запись **float**.

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromStart(float value) override
```

## Примечания


Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Добавить звуковой фрейм
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Установить время обрезки с начала 1.5 секунды
audioFrame->set_TrimFromStart(1500.0f);
```

## См. также

* Класс [AudioFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)