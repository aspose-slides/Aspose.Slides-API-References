---
title: get_StopPreviousSound()
second_title: Référence de l'API Aspose.Slides pour C++
description: Cet attribut indique si l'effet d'animation arrête le son précédent. Lecture bool.
type: docs
weight: 196
url: /fr/aspose.slides.animation/ieffect/get_stopprevioussound/
---
## IEffect::get_StopPreviousSound() méthode


Cet attribut indique si l'effet d'animation arrête le son précédent. Lecture **bool**.

```cpp
virtual bool Aspose::Slides::Animation::IEffect::get_StopPreviousSound()=0
```

## Remarques



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Obtient le premier effet de la première diapositive.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// Obtient le premier effet de la deuxième diapositive.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // Modifie le deuxième effet Enhancements/Sound en "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Voir aussi

* Classe [IEffect](../)
* Espace de noms [Aspose::Slides::Animation](../../)
* Bibliothèque [Aspose.Slides](../../../)