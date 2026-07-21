---
title: set_Sound()
second_title: Aspose.Slides для C++: справочник API
description: Определён встроенный звук для эффекта. Запишите IAudio.
type: docs
weight: 183
url: /ru/aspose.slides.animation/effect/set_sound/
---
## Effect::set_Sound(System::SharedPtr\<IAudio\>) метод


Определён встроенный звук для эффекта. Запишите [IAudio](../../../aspose.slides/iaudio/).

```cpp
void Aspose::Slides::Animation::Effect::set_Sound(System::SharedPtr<IAudio> value) override
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

    // Извлекает звук эффекта в массив байтов
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```




## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IAudio](../../../aspose.slides/iaudio/)
* Класс [Effect](../)
* Пространство имён [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)