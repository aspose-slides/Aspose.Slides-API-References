---
title: set_TrimFromEnd()
second_title: Aspose.Slides для C++ API Reference
description: Указывает продолжительность времени, которую необходимо удалить с конца медиа при воспроизведении, в миллисекундах. Запишите float.
type: docs
weight: 443
url: /ru/aspose.slides/iaudioframe/set_trimfromend/
---
## IAudioFrame::set_TrimFromEnd(float) метод

Указывает продолжительность времени, которую следует удалить с конца медиа при воспроизведении, в миллисекундах. Запишите **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromEnd(float value)=0
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

## См. также

* Класс [IAudioFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)