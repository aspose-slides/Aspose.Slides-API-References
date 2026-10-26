---
title: get_Rewind()
second_title: Aspose.Slides pro C++ API referenci
description: Tento atribut určuje, zda se efekt po dokončení přehrávání přetočí zpět. Čte bool.
type: docs
weight: 313
url: /cs/aspose.slides.animation/itiming/get_rewind/
---
## ITiming::get_Rewind() metoda


Tento atribut určuje, zda se efekt po dokončení přehrávání přetočí zpět. Čte **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_Rewind()=0
```

## Poznámky



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Získá sekvenci efektů pro první snímek
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Získá první efekt hlavní sekvence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Zapne Timing/Rewind efektu.
effect->get_Timing()->set_Rewind(true);
```

## Viz také

* Třída [ITiming](../)
* Jmenný prostor [Aspose::Slides::Animation](../../)
* Knihovna [Aspose.Slides](../../../)