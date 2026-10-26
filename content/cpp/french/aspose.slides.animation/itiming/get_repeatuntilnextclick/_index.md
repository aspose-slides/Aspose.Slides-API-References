---
title: get_RepeatUntilNextClick()
second_title: Référence de l'API Aspose.Slides pour C++
description: Cet attribut indique si l'effet se répétera jusqu'au prochain clic. Lire bool.
type: docs
weight: 157
url: /fr/aspose.slides.animation/itiming/get_repeatuntilnextclick/
---
## ITiming::get_RepeatUntilNextClick() méthode

Cet attribut indique si l'effet se répétera jusqu'au prochain clic. Lire **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilNextClick()=0
```

## Remarques

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Récupère la séquence d'effets pour la première diapositive
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Récupère le premier effet de la séquence principale.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Modifie le Timing/Répétition de l'effet à "Jusqu'à la fin de la diapositive"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## Voir aussi

* Classe [ITiming](../)
* Espace de noms [Aspose::Slides::Animation](../../)
* Bibliothèque [Aspose.Slides](../../../)