---
title: set_AfterAnimationType()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit un type d'animation après pour l'effet. Écrivez AfterAnimationType.
type: docs
weight: 235
url: /fr/aspose.slides.animation/ieffect/set_afteranimationtype/
---
## IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) méthode


Définit un type d'animation après pour l'effet. Écrivez [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value)=0
```

## Remarques



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Obtient le premier effet de la première diapositive.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Modifie l'animation après l'effet en "Masquer au prochain clic de souris"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Voir aussi

* Enum [AfterAnimationType](../../afteranimationtype/)
* Classe [IEffect](../)
* Espace de noms [Aspose::Slides::Animation](../../)
* Bibliothèque [Aspose.Slides](../../../)