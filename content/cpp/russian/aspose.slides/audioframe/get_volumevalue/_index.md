---
title: get_VolumeValue()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает громкость аудио в процентах. Чтение float.
type: docs
weight: 378
url: /ru/aspose.slides/audioframe/get_volumevalue/
---
## AudioFrame::get_VolumeValue() метод


Возвращает громкость аудио в процентах. Чтение **float**.

```cpp
float Aspose::Slides::AudioFrame::get_VolumeValue() override
```

## Примечания


Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Добавить аудио-кадр
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Установить длительность начального затухания на 200 мс
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## См. также

* Класс [AudioFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)