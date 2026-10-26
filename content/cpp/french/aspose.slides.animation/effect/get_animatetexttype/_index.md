---
title: get_AnimateTextType()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit un type de texte animé pour l'effet. Le texte de la forme peut être animé par lettre, par mot ou en une seule fois. Lire AnimateTextType.
type: docs
weight: 274
url: /fr/aspose.slides.animation/effect/get_animatetexttype/
---
## Effect::get_AnimateTextType() méthode

Définit un type de texte animé pour l'effet. Le texte de la forme peut être animé par lettre, par mot ou en une seule fois. Lire [AnimateTextType](../../animatetexttype/).

```cpp
Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::Effect::get_AnimateTextType() override
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
* Classe [Effect](../)
* Espace de noms [Aspose::Slides::Animation](../../)
* Bibliothèque [Aspose.Slides](../../../)