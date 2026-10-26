---
title: get_RepeatUntilEndSlide()
second_title: Référence de l'API Aspose.Slides pour C++
description: Cet attribut indique si l'effet se répétera jusqu'à la fin de la diapositive. Lire bool.
type: docs
weight: 131
url: /fr/aspose.slides.animation/itiming/get_repeatuntilendslide/
---
## ITiming::get_RepeatUntilEndSlide() méthode

Cet attribut indique si l'effet se répétera jusqu'à la fin de la diapositive. Lire **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilEndSlide()=0
```

## Remarques



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Récupère la séquence d'effets pour la première diapositive
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Récupère le premier effet de la séquence principale.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Modifie le Timing/Repeat de l'effet à "Until End of Slide"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## Voir aussi

* Classe [ITiming](../)
* Espace de noms [Aspose::Slides::Animation](../../)
* Bibliothèque [Aspose.Slides](../../../)