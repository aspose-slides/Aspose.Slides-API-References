---
title: set_DelayBetweenTextParts()
second_title: Aspose.Slides pro C++ – reference API
description: Definuje zpoždění mezi animovanými částmi textu (slovy nebo písmeny). Kladná hodnota určuje procento trvání efektu. Záporná hodnota určuje zpoždění v sekundách. Zapište float.
type: docs
weight: 313
url: /cs/aspose.slides.animation/effect/set_delaybetweentextparts/
---
## Effect::set_DelayBetweenTextParts(float) metoda


Definuje zpoždění mezi animovanými částmi textu (slovy nebo písmeny). Kladná hodnota určuje procento trvání efektu. Záporná hodnota určuje zpoždění v sekundách. Zapište **float**.

```cpp
void Aspose::Slides::Animation::Effect::set_DelayBetweenTextParts(float value) override
```

## Poznámky



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Set the delay between animated text parts to 20% of effect duration.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## Viz také

* Třída [Effect](../)
* Jmenný prostor [Aspose::Slides::Animation](../../)
* Knihovna [Aspose.Slides](../../../)