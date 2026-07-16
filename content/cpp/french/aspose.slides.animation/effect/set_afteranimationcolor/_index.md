---
title: set_AfterAnimationColor()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit une couleur après animation pour l'effet. Écrivez IColorFormat.
type: docs
weight: 261
url: /fr/aspose.slides.animation/effect/set_afteranimationcolor/
---
## Effect::set_AfterAnimationColor(System::SharedPtr\<IColorFormat\>) méthode

Définit une couleur après animation pour l'effet. Écrivez [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
void Aspose::Slides::Animation::Effect::set_AfterAnimationColor(System::SharedPtr<IColorFormat> value) override
```

## Remarques



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation type to "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Set the effect After animation color.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IColorFormat](../../../aspose.slides/icolorformat/)
* Classe [Effect](../)
* Espace de noms [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)