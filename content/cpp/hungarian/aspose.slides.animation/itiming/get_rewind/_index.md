---
title: get_Rewind()
second_title: Aspose.Slides C++ API referencia
description: Ez az attribútum meghatározza, hogy a hatás visszatekerő legyen-e a lejátszás befejezése után. Olvasás bool.
type: docs
weight: 313
url: /hu/aspose.slides.animation/itiming/get_rewind/
---
## ITiming::get_Rewind() metódus


Ez az attribútum meghatározza, hogy a hatás visszatekerő legyen-e a lejátszás befejezése után. Olvasás **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_Rewind()=0
```

## Megjegyzés



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Az első dia effektussorozatának lekérése
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// A fő sorozat első effektusának lekérése.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Az effektus Időzítés/Visszatekerés bekapcsolása.
effect->get_Timing()->set_Rewind(true);
```

## Lásd még

* Osztály [ITiming](../)
* Névterület [Aspose::Slides::Animation](../../)
* Könyvtár [Aspose.Slides](../../../)