---
title: set_RepeatUntilNextClick()
second_title: Aspose.Slides C++ API referenciája
description: Ez a tulajdonság meghatározza, hogy a hatás a következő kattintásig ismétlődik-e. Írja bool.
type: docs
weight: 170
url: /hu/aspose.slides.animation/itiming/set_repeatuntilnextclick/
---
## ITiming::set_RepeatUntilNextClick(bool) metódus

Ez a tulajdonság meghatározza, hogy a hatás a következő kattintásig ismétlődik-e. Írja **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilNextClick(bool value)=0
```

## Megjegyzések

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Lekéri az első dia effektus sorozatát
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Lekéri a fő sorozat első effektjét.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Az effekt időzítését/ismétlését "Until End of Slide"-ra állítja
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## Lásd még

* Osztály [ITiming](../)
* Névtér [Aspose::Slides::Animation](../../)
* Könyvtár [Aspose.Slides](../../../)