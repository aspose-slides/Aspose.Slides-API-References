---
title: get_AnimateTextType()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit un type d'animation de texte pour l'effet. Le texte de la forme peut être animé par lettre, par mot ou en une fois. Lire AnimateTextType.
type: docs
weight: 274
url: /fr/aspose.slides.animation/ieffect/get_animatetexttype/
---
## IEffect::get_AnimateTextType() méthode

Définit un type d'animation de texte pour l'effet. Le texte de la forme peut être animé par lettre, par mot ou en une fois. Lire [AnimateTextType](../../animatetexttype/).

```cpp
virtual Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::IEffect::get_AnimateTextType()=0
```

## Remarques



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Récupère le premier effet de la première diapositive.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Modifie le type d'animation du texte de l'effet en "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Voir aussi

* Enum [AnimateTextType](../../animatetexttype/)
* Classe [IEffect](../)
* Espace de noms [Aspose::Slides::Animation](../../)
* Bibliothèque [Aspose.Slides](../../../)