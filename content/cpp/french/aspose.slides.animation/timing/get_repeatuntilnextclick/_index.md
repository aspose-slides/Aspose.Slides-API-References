---
title: get_RepeatUntilNextClick()
second_title: Référence de l'API Aspose.Slides pour C++
description: Cet attribut indique si l'effet se répétera jusqu'au prochain clic. Lire bool.
type: docs
weight: 157
url: /fr/aspose.slides.animation/timing/get_repeatuntilnextclick/
---
## Timing::get_RepeatUntilNextClick() méthode


Cet attribut indique si l'effet se répétera jusqu'au prochain clic. Lire **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_RepeatUntilNextClick() override
```

## Remarques



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## Voir aussi

* Classe [Timing](../)
* Espace de noms [Aspose::Slides::Animation](../../)
* Bibliothèque [Aspose.Slides](../../../)