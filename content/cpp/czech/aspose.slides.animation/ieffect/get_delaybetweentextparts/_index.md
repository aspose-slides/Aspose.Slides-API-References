---
title: get_DelayBetweenTextParts()
second_title: Aspose.Slides pro C++ API Reference
description: Definuje zpoždění mezi animovanými částmi textu (slova nebo písmena). Kladná hodnota určuje procento trvání efektu. Záporná hodnota určuje zpoždění v sekundách. Čte se float.
type: docs
weight: 300
url: /cs/aspose.slides.animation/ieffect/get_delaybetweentextparts/
---
## IEffect::get_DelayBetweenTextParts() metoda


Definuje zpoždění mezi animovanými částmi textu (slova nebo písmena). Kladná hodnota určuje procento trvání efektu. Záporná hodnota určuje zpoždění v sekundách. Čte se **float**.

```cpp
virtual float Aspose::Slides::Animation::IEffect::get_DelayBetweenTextParts()=0
```

## Poznámky



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Získá první efekt na první snímku.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Změní typ animace textu efektu na "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Nastaví zpoždění mezi animovanými částmi textu na 20% trvání efektu.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## Viz také

* Třída [IEffect](../)
* Jmenný prostor [Aspose::Slides::Animation](../../)
* Knihovna [Aspose.Slides](../../../)