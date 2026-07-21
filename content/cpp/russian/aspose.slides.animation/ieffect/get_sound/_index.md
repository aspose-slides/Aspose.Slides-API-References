---
title: get_Sound()
second_title: Aspose.Slides для C++ справочник API
description: Определённый встроенный звук для эффекта. Читайте IAudio.
type: docs
weight: 170
url: /ru/aspose.slides.animation/ieffect/get_sound/
---
## IEffect::get_Sound() метод


Определённый встроенный звук для эффекта. Читайте [IAudio](../../../aspose.slides/iaudio/).

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::Animation::IEffect::get_Sound()=0
```

## Замечания



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// Получает последовательность эффектов для слайда
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // Извлекает звук эффекта в виде массива байтов
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IAudio](../../../aspose.slides/iaudio/)
* Класс [IEffect](../)
* Пространство имён [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)