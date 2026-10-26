---
title: get_AdvanceAfter()
second_title: Référence API Aspose.Slides pour C++
description: Cet attribut spécifie si le diaporama passera à la diapositive suivante après un certain temps. Lecture bool.
type: docs
weight: 105
url: /fr/aspose.slides/islideshowtransition/get_advanceafter/
---
## ISlideShowTransition::get_AdvanceAfter() méthode


Cet attribut spécifie si le diaporama passera à la diapositive suivante après un certain temps. Lecture **bool**.

```cpp
virtual bool Aspose::Slides::ISlideShowTransition::get_AdvanceAfter()=0
```

## Remarques



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Obtenir la première transition de diapositive
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Vérifier si le drapeau Advance Slide After est coché
if (slideTransition->get_AdvanceAfter())
{
    // Obtenir la valeur du temps Advance Slide After
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Voir aussi

* Classe [ISlideShowTransition](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)