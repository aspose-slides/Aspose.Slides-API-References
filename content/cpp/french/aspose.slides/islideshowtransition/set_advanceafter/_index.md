---
title: set_AdvanceAfter()
second_title: Référence API Aspose.Slides pour C++
description: Cet attribut indique si le diaporama passera à la diapositive suivante après un certain temps. Écrivez bool.
type: docs
weight: 118
url: /fr/aspose.slides/islideshowtransition/set_advanceafter/
---
## ISlideShowTransition::set_AdvanceAfter(bool) méthode


Cet attribut indique si le diaporama passera à la diapositive suivante après un certain temps. Écrivez **bool**.

```cpp
virtual void Aspose::Slides::ISlideShowTransition::set_AdvanceAfter(bool value)=0
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