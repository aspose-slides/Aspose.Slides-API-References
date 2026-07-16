---
title: set_AdvanceAfter()
second_title: Référence de l'API Aspose.Slides pour C++
description: Cet attribut spécifie si le diaporama passera à la diapositive suivante après un certain temps. Écrivez bool.
type: docs
weight: 118
url: /fr/aspose.slides.slideshow/slideshowtransition/set_advanceafter/
---
## SlideShowTransition::set_AdvanceAfter(bool) méthode


Cet attribut spécifie si le diaporama passera à la diapositive suivante après un certain temps. Écrivez **bool**.

```cpp
void Aspose::Slides::SlideShow::SlideShowTransition::set_AdvanceAfter(bool value) override
```

## Remarques



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Obtenir la première transition de diapositive
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Vérifier si le drapeau d'avance de la diapositive est coché
if (slideTransition->get_AdvanceAfter())
{
    // Obtenir la valeur du temps d'avance de la diapositive
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Voir également

* classe [SlideShowTransition](../)
* espace de noms [Aspose::Slides::SlideShow](../../)
* Bibliothèque [Aspose.Slides](../../../)