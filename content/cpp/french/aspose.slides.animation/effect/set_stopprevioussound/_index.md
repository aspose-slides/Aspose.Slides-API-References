---
title: set_StopPreviousSound()
second_title: Référence de l'API Aspose.Slides for C++
description: Cet attribut indique si l'effet d'animation arrête le son précédent. Écrire bool.
type: docs
weight: 209
url: /fr/aspose.slides.animation/effect/set_stopprevioussound/
---
## Effect::set_StopPreviousSound(bool) méthode


Cet attribut indique si l'effet d'animation arrête le son précédent. Écrire **bool**.

```cpp
void Aspose::Slides::Animation::Effect::set_StopPreviousSound(bool value) override
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

* Classe [Effect](../)
* Espace de noms [Aspose::Slides::Animation](../../)
* Bibliothèque [Aspose.Slides](../../../)