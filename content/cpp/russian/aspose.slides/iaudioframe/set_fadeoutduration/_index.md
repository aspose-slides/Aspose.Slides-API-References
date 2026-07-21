---
title: set_FadeOutDuration()
second_title: Aspose.Slides для C++ справочник API
description: Указывает продолжительность времени окончания затухания медиа в миллисекундах. Запишите float.
type: docs
weight: 365
url: /ru/aspose.slides/iaudioframe/set_fadeoutduration/
---
## IAudioFrame::set_FadeOutDuration(float) метод


Указывает продолжительность времени окончания постепенного затухания медиа в миллисекундах. Запишите **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_FadeOutDuration(float value)=0
```

## Примечания


Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Добавить аудио кадр
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Установить длительность конечного затухания в 500 мс
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## См. также

* Класс [IAudioFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)