---
title: set_Rewind()
second_title: Référence API Aspose.Slides pour C++
description: Cet attribut spécifie si l'effet reviendra en arrière une fois la lecture terminée. Écrivez bool.
type: docs
weight: 248
url: /fr/aspose.slides.animation/timing/set_rewind/
---
## Timing::set_Rewind(bool) méthode


Cet attribut spécifie si l'effet reviendra en arrière une fois la lecture terminée. Écrivez **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_Rewind(bool value) override
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