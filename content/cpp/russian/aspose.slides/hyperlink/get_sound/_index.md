---
title: get_Sound()
second_title: Aspose.Slides для C++ справочник API
description: Представляет воспроизводимый звук гиперссылки. Читать IAudio.
type: docs
weight: 287
url: /ru/aspose.slides/hyperlink/get_sound/
---
## Hyperlink::get_Sound() метод


Представляет воспроизводимый звук гиперссылки. Читать [IAudio](../../iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Hyperlink::get_Sound() override
```

## Примечания



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Получить гиперссылку первого shape
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Извлечь звук гиперссылки в массив байтов
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IAudio](../../iaudio/)
* Класс [Hyperlink](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)