---
title: set_AfterAnimationType()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit un type d'animation après pour l'effet. Écrivez AfterAnimationType.
type: docs
weight: 235
url: /fr/aspose.slides.animation/effect/set_afteranimationtype/
---
## Effect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) method

Définit un type d'animation après pour l'effet. Écrivez [AfterAnimationType](../../afteranimationtype/).

```cpp
void Aspose::Slides::Animation::Effect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value) override
```

## Remarques


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Récupérer le premier effet de la première diapositive.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Modifier l'effet After animation en "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Voir aussi

* Enum [AfterAnimationType](../../afteranimationtype/)
* Classe [Effect](../)
* Espace de noms [Aspose::Slides::Animation](../../)
* Bibliothèque [Aspose.Slides](../../../)