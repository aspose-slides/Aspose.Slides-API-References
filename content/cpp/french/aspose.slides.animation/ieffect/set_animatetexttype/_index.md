---
title: set_AnimateTextType()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit un type d'animation de texte pour l'effet. Le texte de la forme peut être animé par lettre, par mot ou en une fois. Écrivez AnimateTextType.
type: docs
weight: 287
url: /fr/aspose.slides.animation/ieffect/set_animatetexttype/
---
## IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) méthode

Définit un type d'animation de texte pour l'effet. Le texte de la forme peut être animé par lettre, par mot ou en une fois. Écrivez [AnimateTextType](../../animatetexttype/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value)=0
```

## Remarques



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Voir aussi

* Enum [AnimateTextType](../../animatetexttype/)
* Classe [IEffect](../)
* Espace de noms [Aspose::Slides::Animation](../../)
* Bibliothèque [Aspose.Slides](../../../)