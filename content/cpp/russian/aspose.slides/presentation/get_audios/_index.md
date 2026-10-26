---
title: get_Audios()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает коллекцию всех встроенных аудио-файлов в презентации. Только для чтения IAudioCollection.
type: docs
weight: 222
url: /ru/aspose.slides/presentation/get_audios/
---
## Presentation::get_Audios() метод

Возвращает коллекцию всех встроенных аудио-файлов в презентации. Только для чтения [IAudioCollection](../../iaudiocollection/).

```cpp
System::SharedPtr<IAudioCollection> Aspose::Slides::Presentation::get_Audios() override
```

## Примечания

Следующий пример показывает, как добавить гиперссылку на аудио-файл. 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"audio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(10.0f, 10.0f, 100.0f, 100.0f, audio);
audioFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
audioFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IAudioCollection](../../iaudiocollection/)
* Класс [Presentation](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)