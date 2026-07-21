---
title: set_VolumeValue()
second_title: Aspose.Slides для C++: справочник API
description: Устанавливает громкость аудио в процентах. Записывает float.
type: docs
weight: 391
url: /ru/aspose.slides/iaudioframe/set_volumevalue/
---
## IAudioFrame::set_VolumeValue(float) метод


Устанавливает громкость аудио в процентах. Записывает **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_VolumeValue(float value)=0
```

## Замечания


Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Добавить аудио-кадр
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Установить длительность начального затухания в 200 мс
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## См. также

* Класс [IAudioFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)