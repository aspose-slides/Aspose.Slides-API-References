---
title: get_RepeatUntilEndSlide()
second_title: Référence API Aspose.Slides pour C++
description: Cet attribut indique si l'effet sera répété jusqu'à la fin de la diapositive. Lire bool.
type: docs
weight: 131
url: /fr/aspose.slides.animation/timing/get_repeatuntilendslide/
---
## Timing::get_RepeatUntilEndSlide() méthode

Cet attribut indique si l'effet sera répété jusqu'à la fin de la diapositive. Lire **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_RepeatUntilEndSlide() override
```

## Remarques



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## Voir aussi

* Classe [Timing](../)
* Espace de noms [Aspose::Slides::Animation](../../)
* Bibliothèque [Aspose.Slides](../../../)