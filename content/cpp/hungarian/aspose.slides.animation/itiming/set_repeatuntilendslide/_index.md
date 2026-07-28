---
title: set_RepeatUntilEndSlide()
second_title: Aspose.Slides C++ API referencia
description: Ez az attribútum megadja, hogy a hatás a dia végéig ismétlődik-e. Írja bool.
type: docs
weight: 144
url: /hu/aspose.slides.animation/itiming/set_repeatuntilendslide/
---
## ITiming::set_RepeatUntilEndSlide(bool) metódus


Ez az attribútum meghatározza, hogy a hatás a dia végéig ismétlődik-e. Írja **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilEndSlide(bool value)=0
```

## Megjegyzések



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Lekéri az első dia effektus sorozatát
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Lekéri a fő sorozat első effektusát.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Módosítja az effektus időzítés/ismétlés beállítását "A dia végéig"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## Lásd még

* Osztály [ITiming](../)
* Névtere [Aspose::Slides::Animation](../../)
* Könyvtár [Aspose.Slides](../../../)