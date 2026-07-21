---
title: get_CaptionTracks()
second_title: Aspose.Slides для C++ API Справочник
description: Получает коллекцию закрытых субтитров, связанных с видеокадром. Это свойство только для чтения и возвращает ICaptionsCollection, содержащий все дорожки субтитров.
type: docs
weight: 261
url: /ru/aspose.slides/videoframe/get_captiontracks/
---
## VideoFrame::get_CaptionTracks() метод


Получает коллекцию закрытых субтитров, связанных с видеокадром. Это свойство только для чтения и возвращает [ICaptionsCollection](../../icaptionscollection/), содержащий все дорожки субтитров.

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::VideoFrame::get_CaptionTracks() override
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
        // Извлекает бинарные данные субтитров и сохраняет их в файл
        System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
    }
}
```

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [ICaptionsCollection](../../icaptionscollection/)
* Класс [VideoFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)