---
title: set_Rewind()
second_title: Référence API Aspose.Slides pour C++
description: Cet attribut indique si l'effet reviendra en arrière une fois la lecture terminée. Écrivez bool.
type: docs
weight: 326
url: /fr/aspose.slides.animation/itiming/set_rewind/
---
## ITiming::set_Rewind(bool) méthode


Cet attribut indique si l'effet reviendra en arrière une fois la lecture terminée. Écrivez **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_Rewind(bool value)=0
```

## Remarques



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Get the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Turn the effect Timing/Rewind on.
effect->get_Timing()->set_Rewind(true);
```

## Voir aussi

* Classe [ITiming](../)
* Espace de noms [Aspose::Slides::Animation](../../)
* Bibliothèque [Aspose.Slides](../../../)