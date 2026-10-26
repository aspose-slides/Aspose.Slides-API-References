---
title: get_TrimFromEnd()
second_title: Справочник API Aspose.Slides для C++
description: Указывает продолжительность времени, которую следует удалить с конца медиа при воспроизведении, в миллисекундах. Только для чтения float.
type: docs
weight: 430
url: /ru/aspose.slides/iaudioframe/get_trimfromend/
---
## IAudioFrame::get_TrimFromEnd() метод


Указывает продолжительность времени, которую следует удалить с конца медиа при воспроизведении, в миллисекундах. Только для чтения **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromEnd()=0
```

## Примечания


Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Добавить аудио-кадр
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Установить время обрезки в конце 2 секунды
audioFrame->set_TrimFromEnd(2000.0f);
```

## См. также

* Класс [IAudioFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)