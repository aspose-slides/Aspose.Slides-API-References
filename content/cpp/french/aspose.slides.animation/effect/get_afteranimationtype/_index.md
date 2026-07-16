---
title: get_AfterAnimationType()
second_title: Référence API Aspose.Slides pour C++
description: Définit un type d'animation après pour l'effet. Lire AfterAnimationType.
type: docs
weight: 222
url: /fr/aspose.slides.animation/effect/get_afteranimationtype/
---
## Effect::get_AfterAnimationType() méthode

Définit un type d'animation après pour l'effet. Lire [AfterAnimationType](../../afteranimationtype/).

```cpp
Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::Effect::get_AfterAnimationType() override
```

## Remarques

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Obtenir le premier effet de la première diapositive.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Modifier le type d'animation après l'effet en "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Voir aussi

* Enum [AfterAnimationType](../../afteranimationtype/)
* Class [Effect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Bibliothèque [Aspose.Slides](../../../)