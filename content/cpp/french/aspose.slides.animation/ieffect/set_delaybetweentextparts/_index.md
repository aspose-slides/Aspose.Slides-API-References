---
title: set_DelayBetweenTextParts()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit un délai entre les parties de texte animées (mots ou lettres). Une valeur positive indique le pourcentage de la durée de l'effet. Une valeur négative indique le délai en secondes. Écrire float.
type: docs
weight: 313
url: /fr/aspose.slides.animation/ieffect/set_delaybetweentextparts/
---
## IEffect::set_DelayBetweenTextParts(float) méthode


Définit un délai entre les parties de texte animées (mots ou lettres). Une valeur positive indique le pourcentage de la durée de l'effet. Une valeur négative indique le délai en secondes. Écrire **float**.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_DelayBetweenTextParts(float value)=0
```

## Remarques



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Set the delay between animated text parts to 20% of effect duration.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## Voir aussi

* Classe [IEffect](../)
* Espace de noms [Aspose::Slides::Animation](../../)
* Bibliothèque [Aspose.Slides](../../../)