---
title: get_CaptionTracks()
second_title: Aspose.Slides для C++ справочника API
description: Получает коллекцию закрытых субтитров, связанных с аудио-кадром. Это свойство только для чтения и возвращает ICaptionsCollection, содержащий все дорожки субтитров.
type: docs
weight: 261
url: /ru/aspose.slides/ivideoframe/get_captiontracks/
---
## IVideoFrame::get_CaptionTracks() метод


Получает коллекцию закрытых субтитров, связанных с аудио-кадром. Это свойство только для чтения и возвращает [ICaptionsCollection](../../icaptionscollection/), содержащий все дорожки субтитров.

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IVideoFrame::get_CaptionTracks()=0
```

## Примечания


Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"video with captions.pptx");

for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    System::SharedPtr<IVideoFrame> videoFrame = System::AsCast<IVideoFrame>(shape);
    if (videoFrame != nullptr)
    {
        continue;
    }

    for (auto&& captionTrack : videoFrame->get_CaptionTracks())
    {
        // Извлекает двоичные данные субтитров и сохраняет их в файл
        System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
    }
}
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ICaptionsCollection](../../icaptionscollection/)
* Класс [IVideoFrame](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)