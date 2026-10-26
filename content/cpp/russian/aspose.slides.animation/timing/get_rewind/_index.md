---
title: get_Rewind()
second_title: Aspose.Slides для C++ Справочник API
description: Этот атрибут указывает, будет ли эффект перематываться назад после завершения воспроизведения. Читается bool.
type: docs
weight: 235
url: /ru/aspose.slides.animation/timing/get_rewind/
---
## Timing::get_Rewind() метод

Этот атрибут указывает, будет ли эффект перематываться назад после завершения воспроизведения. Читается **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_Rewind() override
```

## Примечания

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Get the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Turn the effect Timing/Rewind on.
effect->get_Timing()->set_Rewind(true);
```

## Смотрите также

* Класс [Timing](../)
* Пространство имен [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)