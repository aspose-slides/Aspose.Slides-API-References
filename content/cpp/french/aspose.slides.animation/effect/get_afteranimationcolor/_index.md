---
title: get_AfterAnimationColor()
second_title: Référence API Aspose.Slides pour C++
description: Définit une couleur après l'animation pour l'effet. Lire IColorFormat.
type: docs
weight: 248
url: /fr/aspose.slides.animation/effect/get_afteranimationcolor/
---
## Effect::get_AfterAnimationColor() méthode


Définit une couleur après l'animation pour l'effet. Lire [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
System::SharedPtr<IColorFormat> Aspose::Slides::Animation::Effect::get_AfterAnimationColor() override
```

## Remarques



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Obtenez le premier effet de la première diapositive.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Modifiez le type d'animation après en "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Définissez la couleur d'animation après l'effet.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IColorFormat](../../../aspose.slides/icolorformat/)
* Classe [Effect](../)
* Espace de noms [Aspose::Slides::Animation](../../)
* Bibliothèque [Aspose.Slides](../../../)