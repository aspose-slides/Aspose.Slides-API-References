---
title: set_StopPreviousSound()
second_title: Référence de l'API Aspose.Slides pour C++
description: Cet attribut indique si l'effet d'animation arrête le son précédent. Écrivez bool.
type: docs
weight: 209
url: /fr/aspose.slides.animation/ieffect/set_stopprevioussound/
---
## IEffect::set_StopPreviousSound(bool) méthode


Cet attribut indique si l'effet d'animation arrête le son précédent. Écrivez **bool**.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_StopPreviousSound(bool value)=0
```

## Remarques



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Obtenir le premier effet de la première diapositive.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// Obtenir le premier effet de la deuxième diapositive.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // Modifier le deuxième effet Enhancements/Sound en "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Voir aussi

* Classe [IEffect](../)
* Espace de noms [Aspose::Slides::Animation](../../)
* Bibliothèque [Aspose.Slides](../../../)