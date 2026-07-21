---
title: set_TrimFromEnd()
second_title: Справочник API Aspose.Slides для C++
description: Указывает длительность времени, которую следует удалить с конца медиа при воспроизведении, в миллисекундах. Запишите float.
type: docs
weight: 443
url: /ru/aspose.slides/audioframe/set_trimfromend/
---
## AudioFrame::set_TrimFromEnd(float) метод


Указывает длительность времени, которую следует удалить с конца медиа при воспроизведении, в миллисекундах. Запишите **float**.

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromEnd(float value) override
```

## Примечания


Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Добавить аудио кадр
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Установить время обрезки с конца 2 секунды
audioFrame->set_TrimFromEnd(2000.0f);
```

## Смотрите также

* Класс [AudioFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)