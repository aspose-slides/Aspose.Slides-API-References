---
title: set_Sound()
second_title: Aspose.Slides для справочника API C++
description: Представляет звук, воспроизводимый гиперссылкой. Запишите IAudio.
type: docs
weight: 196
url: /ru/aspose.slides/ihyperlink/set_sound/
---
## IHyperlink::set_Sound(System::SharedPtr\<IAudio\>) метод

Представляет звук, воспроизводимый гиперссылкой. Запишите [IAudio](../../iaudio/).

```cpp
virtual void Aspose::Slides::IHyperlink::set_Sound(System::SharedPtr<IAudio> value)=0
```

## Примечания

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Получить гиперссылку первого объекта формы
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Извлечь звук гиперссылки в массив байтов
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IAudio](../../iaudio/)
* Класс [IHyperlink](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)