---
title: get_Rewind()
second_title: Référence de l'API Aspose.Slides pour C++
description: Cet attribut indique si l'effet reviendra en arrière une fois la lecture terminée. Lecture bool.
type: docs
weight: 235
url: /fr/aspose.slides.animation/timing/get_rewind/
---
## Timing::get_Rewind() méthode


Cet attribut indique si l'effet reviendra en arrière une fois la lecture terminée. Lecture **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_Rewind() override
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

* Classe [Timing](../)
* Espace de noms [Aspose::Slides::Animation](../../)
* Bibliothèque [Aspose.Slides](../../../)