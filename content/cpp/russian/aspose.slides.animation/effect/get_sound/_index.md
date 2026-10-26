---
title: get_Sound()
second_title: Aspose.Slides для справочника API C++
description: Определённый встроенный звук для эффекта. См. IAudio.
type: docs
weight: 170
url: /ru/aspose.slides.animation/effect/get_sound/
---
## Effect::get_Sound() метод


Определённый встроенный звук для эффекта. См. [IAudio](../../../aspose.slides/iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Animation::Effect::get_Sound() override
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

    // Извлекает звук эффекта в массив байт
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```




## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IAudio](../../../aspose.slides/iaudio/)
* Класс [Effect](../)
* Пространство имён [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)