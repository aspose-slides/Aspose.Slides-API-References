---
title: set_RepeatUntilEndSlide()
second_title: Référence de l'API Aspose.Slides pour C++
description: Cet attribut indique si l'effet se répétera jusqu'à la fin de la diapositive. Écrire bool.
type: docs
weight: 144
url: /fr/aspose.slides.animation/timing/set_repeatuntilendslide/
---
## Timing::set_RepeatUntilEndSlide(bool) méthode

Cet attribut indique si l'effet se répétera jusqu'à la fin de la diapositive. Écrire **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_RepeatUntilEndSlide(bool value) override
```

## Remarques



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Récupère la séquence d'effets de la première diapositive
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Récupère le premier effet de la séquence principale.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Modifie le Timing/Répétition de l'effet à "Jusqu'à la fin de la diapositive"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## Voir aussi

* Classe [Timing](../)
* Espace de noms [Aspose::Slides::Animation](../../)
* Bibliothèque [Aspose.Slides](../../../)