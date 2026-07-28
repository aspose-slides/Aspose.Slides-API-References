---
title: get_RepeatUntilNextClick()
second_title: Aspose.Slides for C++ API referencia
description: Ez az attribútum meghatározza, hogy a hatás a következő kattintásig ismétlődik-e. Olvassa bool.
type: docs
weight: 157
url: /hu/aspose.slides.animation/itiming/get_repeatuntilnextclick/
---
## ITiming::get_RepeatUntilNextClick() metódus


Ez az attribútum meghatározza, hogy a hatás a következő kattintásig ismétlődik-e. Olvassa **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilNextClick()=0
```

## Megjegyzések



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Lekéri az első dia hatássorozatát
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Lekéri a fő sorozat első effektusát.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Megváltoztatja az effektus időzítését/ismétlését "A dia végéig"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## Lásd még

* Osztály [ITiming](../)
* Névtér [Aspose::Slides::Animation](../../)
* Könyvtár [Aspose.Slides](../../../)