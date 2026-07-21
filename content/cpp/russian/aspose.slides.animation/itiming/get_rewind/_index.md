---
title: get_Rewind()
second_title: "Aspose.Slides для C++: справочник API"
description: "Этот атрибут указывает, будет ли эффект перематываться после завершения воспроизведения. Чтение **bool**."
type: docs
weight: 313
url: /ru/aspose.slides.animation/itiming/get_rewind/
---
## ITiming::get_Rewind() метод


Этот атрибут указывает, будет ли эффект перематываться после завершения воспроизведения. Чтение **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_Rewind()=0
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
* Пространство имен [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)