---
title: set_Sound()
second_title: Справочник API Aspose.Slides для C++
description: Определён встроенный звук для эффекта. Запишите IAudio.
type: docs
weight: 183
url: /ru/aspose.slides.animation/ieffect/set_sound/
---
## IEffect::set_Sound(System::SharedPtr\<IAudio\>) метод

Определяет встроенный звук для эффекта. Запишите [IAudio](../../../aspose.slides/iaudio/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_Sound(System::SharedPtr<IAudio> value)=0
```

## Примечания

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

    // Извлекает звук эффекта в массиве байтов
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IAudio](../../../aspose.slides/iaudio/)
* Класс [IEffect](../)
* Пространство имён [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)