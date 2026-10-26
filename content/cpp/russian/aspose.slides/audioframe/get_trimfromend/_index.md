---
title: get_TrimFromEnd()
second_title: Aspose.Slides для C++ справочник API
description: Указывает продолжительность времени, которую следует удалить с конца медиа при воспроизведении, в миллисекундах. Только для чтения float.
type: docs
weight: 430
url: /ru/aspose.slides/audioframe/get_trimfromend/
---
## AudioFrame::get_TrimFromEnd() метод


Указывает продолжительность времени, которую следует удалить с конца медиа при воспроизведении, в миллисекундах. Только для чтения **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromEnd() override
```

## Примечания


Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Добавить аудио-кадр
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Установить время обрезки с конца 2 секунды
audioFrame->set_TrimFromEnd(2000.0f);
```

## См. также

* Класс [AudioFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)