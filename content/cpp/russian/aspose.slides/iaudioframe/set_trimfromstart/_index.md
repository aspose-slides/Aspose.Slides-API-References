---
title: set_TrimFromStart()
second_title: Aspose.Slides для C++ справочник API
description: Указывает продолжительность времени, которую следует удалить с начала медиа при воспроизведении, в миллисекундах. Записать float.
type: docs
weight: 417
url: /ru/aspose.slides/iaudioframe/set_trimfromstart/
---
## IAudioFrame::set_TrimFromStart(float) метод


Указывает продолжительность времени, которую необходимо удалить с начала медиа при воспроизведении, в миллисекундах. Записать **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromStart(float value)=0
```

## Примечания


Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Добавить аудио-кадр
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Установить время обрезки начала 1.5 секунды
audioFrame->set_TrimFromStart(1500.0f);
```

## Смотрите также

* Класс [IAudioFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)