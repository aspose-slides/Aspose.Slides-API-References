---
title: set_RepeatUntilNextClick()
second_title: Référence de l'API Aspose.Slides pour C++
description: Cet attribut indique si l'effet se répétera jusqu'au prochain clic. Écrivez bool.
type: docs
weight: 170
url: /fr/aspose.slides.animation/timing/set_repeatuntilnextclick/
---
## Timing::set_RepeatUntilNextClick(bool) méthode


Cet attribut indique si l'effet se répétera jusqu'au prochain clic. Écrivez **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_RepeatUntilNextClick(bool value) override
```

## Remarques



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Obtient la séquence d'effets pour la première diapositive
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Obtient le premier effet de la séquence principale.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Modifie le Timing/Répétition de l'effet en "Jusqu'à la fin de la diapositive"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## Voir aussi

* Classe [Timing](../)
* Espace de noms [Aspose::Slides::Animation](../../)
* Bibliothèque [Aspose.Slides](../../../)