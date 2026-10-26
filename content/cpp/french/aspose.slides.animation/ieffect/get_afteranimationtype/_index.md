---
title: get_AfterAnimationType()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit un type d'animation après pour l'effet. Lire AfterAnimationType.
type: docs
weight: 222
url: /fr/aspose.slides.animation/ieffect/get_afteranimationtype/
---
## IEffect::get_AfterAnimationType() méthode

Définit un type d'animation après pour l'effet. Lire [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::IEffect::get_AfterAnimationType()=0
```

## Remarques

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Obtenir le premier effet de la première diapositive.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Modifier l'effet After animation en "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Voir aussi

* Enum [AfterAnimationType](../../afteranimationtype/)
* Classe [IEffect](../)
* Espace de noms [Aspose::Slides::Animation](../../)
* Bibliothèque [Aspose.Slides](../../../)