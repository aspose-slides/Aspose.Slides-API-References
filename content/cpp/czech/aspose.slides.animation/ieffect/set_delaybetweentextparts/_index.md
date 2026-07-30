---
title: set_DelayBetweenTextParts()
second_title: Aspose.Slides pro C++ - reference API
description: Definuje zpoždění mezi animovanými částmi textu (slova nebo písmena). Kladná hodnota určuje procento trvání efektu. Záporná hodnota určuje zpoždění v sekundách. Zapište float.
type: docs
weight: 313
url: /cs/aspose.slides.animation/ieffect/set_delaybetweentextparts/
---
## IEffect::set_DelayBetweenTextParts(float) metoda


Definuje zpoždění mezi animovanými částmi textu (slova nebo písmena). Kladná hodnota udává procento trvání efektu. Záporná hodnota udává zpoždění v sekundách. Zapište **float**.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_DelayBetweenTextParts(float value)=0
```

## Poznámky



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Získá první efekt prvního snímku.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Změní typ animace textu efektu na "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Nastaví zpoždění mezi animovanými částmi textu na 20 % trvání efektu.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## Viz také

* Třída [IEffect](../)
* Jmenný prostor [Aspose::Slides::Animation](../../)
* Knihovna [Aspose.Slides](../../../)