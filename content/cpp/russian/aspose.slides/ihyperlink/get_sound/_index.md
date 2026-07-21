---
title: get_Sound()
second_title: Справочник API Aspose.Slides для C++
description: Представляет воспроизводимый звук гиперссылки. См. IAudio.
type: docs
weight: 183
url: /ru/aspose.slides/ihyperlink/get_sound/
---
## IHyperlink::get_Sound() метод


Представляет воспроизводимый звук гиперссылки. См. [IAudio](../../iaudio/).

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IHyperlink::get_Sound()=0
```

## Примечания



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Получить гиперссылку первой фигуры
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Извлечь звук гиперссылки в массив байт
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```




## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudio](../../iaudio/)
* Class [IHyperlink](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)