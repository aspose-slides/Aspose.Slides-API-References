---
title: get_AdvanceAfter()
second_title: Référence de l'API Aspose.Slides pour C++
description: Cet attribut spécifie si le diaporama passera à la diapositive suivante après un certain temps. Lire bool.
type: docs
weight: 105
url: /fr/aspose.slides.slideshow/slideshowtransition/get_advanceafter/
---
## SlideShowTransition::get_AdvanceAfter() méthode


Cet attribut spécifie si le diaporama passera à la diapositive suivante après un certain temps. Lire **bool**.

```cpp
bool Aspose::Slides::SlideShow::SlideShowTransition::get_AdvanceAfter() override
```

## Remarques



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Obtenir la première transition de diapositive
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Vérifier si le drapeau Advance Slide After est activé
if (slideTransition->get_AdvanceAfter())
{
    // Obtenir la valeur du temps Advance Slide After
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Voir aussi

* Classe [SlideShowTransition](../)
* Espace de noms [Aspose::Slides::SlideShow](../../)
* Bibliothèque [Aspose.Slides](../../../)