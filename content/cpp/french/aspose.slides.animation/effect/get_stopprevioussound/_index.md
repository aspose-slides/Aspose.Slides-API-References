---
title: get_StopPreviousSound()
second_title: Référence API Aspose.Slides pour C++
description: Cet attribut indique si l'effet d'animation arrête le son précédent. Lecture bool.
type: docs
weight: 196
url: /fr/aspose.slides.animation/effect/get_stopprevioussound/
---
## Effect::get_StopPreviousSound() méthode


Cet attribut indique si l'effet d'animation arrête le son précédent. Lecture **bool**.

```cpp
bool Aspose::Slides::Animation::Effect::get_StopPreviousSound() override
```

## Remarques



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// Get the first effect of the second slide.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // Modifier le deuxième effet Enhancements/Sound en "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Voir aussi

* Classe [Effect](../)
* Espace de noms [Aspose::Slides::Animation](../../)
* Bibliothèque [Aspose.Slides](../../../)