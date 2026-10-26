---
title: set_Rewind()
second_title: Aspose.Slides для C++ справочника API
description: Этот атрибут указывает, будет ли эффект перематываться после завершения воспроизведения. Запишите bool.
type: docs
weight: 326
url: /ru/aspose.slides.animation/itiming/set_rewind/
---
## ITiming::set_Rewind(bool) метод

Этот атрибут указывает, будет ли эффект перематываться после завершения воспроизведения. Запишите **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_Rewind(bool value)=0
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

* Класс [ITiming](../)
* Пространство имён [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)