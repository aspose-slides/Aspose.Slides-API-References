---
title: set_Sound()
second_title: Aspose.Slides для C++ API Reference
description: Представляет воспроизводимый звук гиперссылки. Запишите IAudio.
type: docs
weight: 300
url: /ru/aspose.slides/hyperlink/set_sound/
---
## Hyperlink::set_Sound(System::SharedPtr\<IAudio\>) метод


Представляет воспроизводимый звук гиперссылки. Запишите [IAudio](../../iaudio/).

```cpp
void Aspose::Slides::Hyperlink::set_Sound(System::SharedPtr<IAudio> value) override
```

## Примечания



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Получить гиперссылку первой формы
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Извлечь звук гиперссылки в массив байт
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IAudio](../../iaudio/)
* Класс [Hyperlink](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)