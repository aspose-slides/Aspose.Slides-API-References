---
title: get_CaptionTracks()
second_title: Aspose.Slides для C++ справочник API
description: Получает коллекцию закрытых субтитров, связанных с аудиокадром. Это свойство только для чтения и возвращает ICaptionsCollection, содержащий все дорожки субтитров.
type: docs
weight: 456
url: /ru/aspose.slides/audioframe/get_captiontracks/
---
## AudioFrame::get_CaptionTracks() метод


Получает коллекцию закрытых субтитров, связанных с аудиокадром. Это свойство только для чтения и возвращает [ICaptionsCollection](../../icaptionscollection/), содержащий все дорожки субтитров.

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::AudioFrame::get_CaptionTracks() override
```

## Примечания


Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"audio with captions.pptx");
for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    if (System::ObjectExt::Is<IAudioFrame>(shape))
    {
        System::SharedPtr<IAudioFrame> audioFrame = System::ExplicitCast<IAudioFrame>(shape);
        // Сохраните бинарные данные дорожки субтитров как файл .vtt
        for (auto&& captionTrack : audioFrame->get_CaptionTracks())
        {
            System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
        }
    }
}
```

## Смотрите также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [ICaptionsCollection](../../icaptionscollection/)
* Класс [AudioFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)