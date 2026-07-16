---
title: get_Rewind()
second_title: Référence de l'API Aspose.Slides pour C++
description: Cet attribut spécifie si l'effet reviendra en arrière une fois la lecture terminée. Lecture bool.
type: docs
weight: 313
url: /fr/aspose.slides.animation/itiming/get_rewind/
---
## ITiming::get_Rewind() méthode


Cet attribut spécifie si l'effet reviendra en arrière une fois la lecture terminée. Lecture **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_Rewind()=0
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