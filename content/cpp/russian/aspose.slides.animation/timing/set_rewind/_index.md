---
title: set_Rewind()
second_title: Справочник API Aspose.Slides для C++
description: Этот атрибут определяет, будет ли эффект перематываться после завершения воспроизведения. Записать bool.
type: docs
weight: 248
url: /ru/aspose.slides.animation/timing/set_rewind/
---
## Timing::set_Rewind(bool) метод


Этот атрибут определяет, будет ли эффект перематываться после завершения воспроизведения. Записать **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_Rewind(bool value) override
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

## См. также

* Класс [Timing](../)
* Пространство имён [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)