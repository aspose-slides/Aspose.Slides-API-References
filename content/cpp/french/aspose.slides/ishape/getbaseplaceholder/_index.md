---
title: GetBasePlaceholder()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie une forme de substitut de base (forme provenant de la disposition et/ou de la diapositive maître dont la forme actuelle hérite).
type: docs
weight: 573
url: /fr/aspose.slides/ishape/getbaseplaceholder/
---
## IShape::GetBasePlaceholder() méthode

Renvoie une forme de substitut de base (forme provenant de la disposition et/ou de la diapositive maître dont la forme actuelle hérite).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShape::GetBasePlaceholder()=0
```

## Remarques

Une valeur null est renvoyée si la forme actuelle n'hérite pas.

```cpp
// obtenir tous les effets animés (maître/disposition/diapositive) de la forme de substitut
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"sample.pptx");

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::SharedPtr<IShape> shape = slide->get_Shape(0);
System::ArrayPtr<System::SharedPtr<IEffect>> shapeEffects = slide->get_Timeline()->get_MainSequence()->GetEffectsByShape(shape);

System::SharedPtr<IShape> layoutShape = shape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> layoutShapeEffects = slide->get_LayoutSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(layoutShape);

System::SharedPtr<IShape> masterShape = layoutShape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> masterShapeEffects = slide->get_LayoutSlide()->get_MasterSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(masterShape);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShape](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)