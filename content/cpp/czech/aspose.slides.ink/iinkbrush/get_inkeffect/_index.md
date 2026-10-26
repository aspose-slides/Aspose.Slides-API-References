---
title: get_InkEffect()
second_title: Aspose.Slides pro C++ API Reference
description: "Získá typ efektu inkoustu (např. Galaxy, Gold, Silver), který definuje vizuální styl tahu inkoustu. Hodnota je načtena z vlastnosti štětce \"inkEffects\". Pokud není zadán žádný rozpoznaný efekt, je vráceno InkEffectType::NotDefined."
type: docs
weight: 53
url: /cs/aspose.slides.ink/iinkbrush/get_inkeffect/
---
## IInkBrush::get_InkEffect() metoda


Získá typ efektu inkoustu (např. Galaxy, Gold, Silver), který definuje vizuální styl tahu inkoustu. Hodnota je načtena z vlastnosti štětce "inkEffects". Pokud není zadán žádný rozpoznaný efekt, je vráceno [InkEffectType::NotDefined](../../inkeffecttype/).

```cpp
virtual InkEffectType Aspose::Slides::Ink::IInkBrush::get_InkEffect()=0
```

## Poznámky


Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<Ink> ink = System::AsCast<Ink>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IInkBrush> brush = ink->get_Traces()->idx_get(0)->get_Brush();
System::Console::WriteLine(u"InkEffects = {0}", brush->get_InkEffect());
```

## Viz také

* Enum [InkEffectType](../../inkeffecttype/)
* Třída [IInkBrush](../)
* Jmenný prostor [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)