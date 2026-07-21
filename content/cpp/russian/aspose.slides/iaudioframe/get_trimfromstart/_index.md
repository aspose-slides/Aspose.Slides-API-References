---
title: get_TrimFromStart()
second_title: Справочник API Aspose.Slides для C++
description: Указывает длительность времени, которую необходимо удалить с начала медиа при воспроизведении, в миллисекундах. Только для чтения float.
type: docs
weight: 404
url: /ru/aspose.slides/iaudioframe/get_trimfromstart/
---
## IAudioFrame::get_TrimFromStart() метод


Указывает длительность времени, которую необходимо удалить с начала медиа при воспроизведении, в миллисекундах. Только для чтения **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromStart()=0
```

## Примечания


Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Добавить аудио-кадр
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Установить время начала обрезки 1.5 секунды
audioFrame->set_TrimFromStart(1500.0f);
```

## См. также

* Класс [IAudioFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)