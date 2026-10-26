---
title: get_CaptionTracks()
second_title: Справочник API Aspose.Slides для C++
description: Получает коллекцию закрытых субтитров, связанных с аудио-кадром. Это свойство только для чтения и возвращает ICaptionsCollection, содержащий все дорожки субтитров.
type: docs
weight: 456
url: /ru/aspose.slides/iaudioframe/get_captiontracks/
---
## IAudioFrame::get_CaptionTracks() метод

Получает коллекцию закрытых субтитров, связанных с аудио-кадром. Это свойство является только для чтения и возвращает [ICaptionsCollection](../../icaptionscollection/), содержащий все дорожки субтитров.

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IAudioFrame::get_CaptionTracks()=0
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
        // Сохранить двоичные данные дорожки субтитров в файл .vtt
        for (auto&& captionTrack : audioFrame->get_CaptionTracks())
        {
            System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
        }
    }
}
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ICaptionsCollection](../../icaptionscollection/)
* Класс [IAudioFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)